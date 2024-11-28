# Use the official MySQL base image
FROM mysql:latest

# Copy initialization script to Docker entrypoint directory
COPY init.sql /docker-entrypoint-initdb.d/

# Set environment variables for MySQL
ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes
ENV MYSQL_DATABASE=UserDatabase
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword
ENV MYSQL_ROOT_PASSWORD=mayank
# ENV MYSQL_ROOT_PASSWORD=rootpassword

# Expose MySQL port
EXPOSE 3306
