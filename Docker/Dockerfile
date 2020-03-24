FROM nginx:alpine
RUN mkdir /usr/share/nginx/html/piw/
COPY ./public /usr/share/nginx/html/piw/
RUN rm /etc/nginx/conf.d/*
COPY ./Docker/nginx.conf /etc/nginx/conf.d/