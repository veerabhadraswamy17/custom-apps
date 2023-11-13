# Use the official NGINX base image
FROM nginx:latest

# Copy custom configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf
COPY app2.html /usr/share/nginx/html/app2/app2.html
COPY styles.css /usr/share/nginx/html/app2/styles.css

# You can add more configurations, SSL certificates, or static content
# For example:
# COPY ssl.crt /etc/nginx/ssl.crt
# COPY ssl.key /etc/nginx/ssl.key
# COPY static-html /usr/share/nginx/html

# # Expose ports if needed
# EXPOSE 80
# EXPOSE 443

# Command to start NGINX when the container runs
CMD ["nginx", "-g", "daemon off;"]
