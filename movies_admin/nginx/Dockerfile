FROM nginx:1.19.0-alpine

RUN rm /etc/nginx/conf.d/default.conf
RUN rm /etc/nginx/nginx.conf
COPY movie_admin.conf /etc/nginx/conf.d
COPY nginx.conf /etc/nginx
