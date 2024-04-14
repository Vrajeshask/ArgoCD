# Use NGINX base image from Docker Hub
FROM nginx:latest

# Copy custom index.html file from host to container
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 to the outside world
EXPOSE 80

# Start NGINX server when the container launches
CMD ["nginx", "-g", "daemon off;"]