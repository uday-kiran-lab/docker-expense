FROM nginx:latest
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf

