# Start from apache base image
FROM httpd:latest

# Copy contents of the camera web interfaces
COPY ./root_dir/ /usr/local/apache2/htdocs/

# Expose to outside containers
EXPOSE 80
