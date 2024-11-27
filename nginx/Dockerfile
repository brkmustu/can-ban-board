FROM nginx:alpine
COPY nginx/nginx.conf /etc/nginx/nginx.conf
COPY nginx/default.conf /etc/nginx/conf.d/default.conf
COPY nginx/cert/server.crt /etc/cert/server.crt
COPY nginx/cert/server.key /etc/cert/server.key
COPY nginx/cert/passwords /etc/cert/passwords
EXPOSE 80 443 8080
