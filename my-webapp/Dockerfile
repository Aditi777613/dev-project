# Use the official Tomcat image from the Docker Hub as a base image
FROM tomcat:9.0-jdk11

# Set environment variables (optional, adjust as needed)
ENV JAVA_OPTS="-Xms512m -Xmx1024m"

# Copy your WAR file into the Tomcat webapps directory
COPY ./path/to/your-webapp.war /usr/local/tomcat/webapps/ROOT.war

# Expose port 8080 (default for Tomcat)
EXPOSE 8080

# Start Tomcat server
CMD ["catalina.sh", "run"]
