# Set the base image to use for subsequent instructions
FROM alpine:3.19

# Copy any source file(s) required for the action
COPY entrypoint.sh /entrypoint.sh

# Enable execution
RUN chmod +x entrypoint.sh

# Configure the container to be run as an executable
ENTRYPOINT ["/entrypoint.sh"]
