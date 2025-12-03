# FROM almalinux:9
# RUN dnf install blind-utils -y
# RUN dnf install mysql -y 
# RUN dnf install telnet -y
# CMD ["sleep","10000"]


FROM almalinux:9

# Update and install required tools
RUN dnf update -y && \
    dnf install -y bind-utils mysql-client telnet && \
    dnf clean all

# Keep the container running for testing
CMD ["sleep", "10000"]
