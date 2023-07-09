FROM docker:latest

# Install AWS CLI
RUN apk -v --update add python3 py-pip groff less \
    && pip install --upgrade pip \
    && pip install awscli

# Install Docker inside the container
RUN apk add --no-cache docker

# Set the default command to run when the container starts
CMD ["bash"]