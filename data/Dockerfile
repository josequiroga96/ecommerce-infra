FROM nginx:1.15.12-alpine
COPY ./default.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
CMD ["nginx-debug", "-g", "daemon off;"]