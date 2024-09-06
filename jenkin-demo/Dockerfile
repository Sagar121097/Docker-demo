# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy your local index.html to the default Nginx directory
COPY ./index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]

