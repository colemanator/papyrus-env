FROM nginx

ARG config

RUN rm /etc/nginx/conf.d/default.conf

COPY $config /etc/nginx/conf.d

