# Use an official Nginx image as the base image
FROM nginx:alpine

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Copy the built React app (assuming the build files are in the current directory)
COPY build/ .

# Expose port 80
EXPOSE 80

# Start Nginx to serve the static files
CMD ["nginx", "-g", "daemon off;"]
