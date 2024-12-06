FROM postgres:13-alpine

# Set environment variables for database configuration
ENV POSTGRES_DB=techdome_db
ENV POSTGRES_USER=techdome_user
ENV POSTGRES_PASSWORD=techdome_password

# Copy initialization script
COPY init.sql /docker-entrypoint-initdb.d/