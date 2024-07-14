# Use the official NGINX image from the Docker Hub
FROM nginx:alpine

# Copy the custom HTML file to the NGINX default location
COPY /files/index.html /usr/share/nginx/html/index.html

# Expose port 80 to the outside world
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
