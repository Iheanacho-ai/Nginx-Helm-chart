FROM nginx:alpine

# Remove default index.html (optional but good hygiene)
RUN rm -rf /usr/share/nginx/html/*

# Copy your custom index.html into the default nginx html directory
COPY index.html /usr/share/nginx/html

