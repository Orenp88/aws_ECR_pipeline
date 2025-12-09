# Use a very small Linux base image
FROM alpine:3.20

# Set a working directory
WORKDIR /app

# Copy everything from your GitHub repo (optional)
COPY . .

# Install anything you want (optional)
# RUN apk add --no-cache curl

# Default command that runs when container starts
CMD ["echo", "ECR Pipeline container is running!"]