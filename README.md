# docker-php-mysql-development-server
  A replacement docker setup for a normal PHP/MySQL/NGINX development server.

# How to use
Add a new folder in the /html-folder. Each folder there represents a subdomain, so when the server is running you can access your page by using the url {subdomain}.localhost.

# Versions
Latest MySQL and Nginx images are used. PHP is set to 8.1.2 currently, but all of this is easy to change for your needs if necessary.

# PHP Extensions
Right now some extensions like zip, pdo, mysqli, gd and imagick is installed, but more can and will be added in the future. And this is also easy to change to suit your needs.

# Wordpress ready
This environment has been successfully tested with the latest version of Wordpress.

# How to use multiple databases
Multiple databases are easy to use! Just log into the server via your favourite MySQL-client and add a database there. Use "root" as the username and "test" as the password.

# In the future
- Sass support, and possibly complete NPM support.
- Automatic or easier way to add database users and multiple databases.
