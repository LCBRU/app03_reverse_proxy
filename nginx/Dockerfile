FROM tutum/nginx
LABEL org.opencontainers.image.authors="Richard Bramley <rabramley@gmail.com>"

RUN rm /etc/nginx/sites-enabled/default
ADD sites-enabled/app03 /etc/nginx/sites-enabled/app03
