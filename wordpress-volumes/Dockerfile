# Use the official WordPress image with Apache
FROM wordpress:latest

# Set the working directory to the WordPress installation
WORKDIR /var/www/html

# Add custom theme or plugin files if needed
# COPY ./custom-theme /var/www/html/wp-content/themes/custom-theme

# Add custom configuration files if needed
COPY ./wordpress-container /var/www/html

# Expose port 80 for HTTP
EXPOSE 80

# Start Apache and WordPress
CMD ["apache2-foreground"]
