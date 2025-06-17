# Use the official lightweight NGINX image
FROM nginx:alpine

# Copy the index.html file to the default NGINX HTML location
COPY index.html /usr/share/nginx/html/

# Expose the default HTTP port
EXPOSE 80

# Start NGINX when the container launches
CMD ["nginx", "-g", "daemon off;"]

