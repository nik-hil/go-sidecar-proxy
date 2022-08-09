# Use the Go v1.18 image for the base.
FROM golang:1.18

# Copy the proxy code to the container.
COPY main.go .

# Run the proxy on container startup.
ENTRYPOINT [ "go" ]
CMD [ "run", "main.go" ]

# Expose the proxy port.
EXPOSE 8000