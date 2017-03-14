FROM nginx:1.11.10

MAINTAINER Tu Nguyen <ladiesman9x@gmail.com>

COPY ./default.conf /etc/nginx/conf.d/
COPY ./nginx.conf.sample /etc/nginx/conf.d/
COPY ./nginx.crt /etc/nginx/
COPY ./nginx.key /etc/nginx/

ENTRYPOINT ["/usr/local/bin/docker-environment"]
CMD ["nginx", "-g", "daemon off;"]
