# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy the static website files into the Nginx document root
COPY landing2 /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Command to start Nginx and serve the static website
CMD ["nginx", "-g", "daemon off;"]
