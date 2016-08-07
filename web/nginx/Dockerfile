FROM nginx

ADD default.conf /etc/nginx/conf.d/default.conf

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime

VOLUME ["/var/projects/data/html"]