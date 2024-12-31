# Use a Node.js base image with version 6.10.3
FROM node:6.10.3

# Set the working directory
WORKDIR /workspace

# Set environment variables (optional)
ENV NODE_ENV=development

RUN npm install -g @angular/cli@1.1.0 
RUN npm install -g typescript

# Expose any ports (optional)
EXPOSE 3000

