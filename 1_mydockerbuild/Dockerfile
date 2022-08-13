FROM nginx:alpine
#RUN echo "My build started"
# Заменяем дефолтную страницу nginx
RUN rm -rf /usr/share/nginx/html/*
COPY ./html /usr/share/nginx/html
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
