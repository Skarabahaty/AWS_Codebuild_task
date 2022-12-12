FROM public.ecr.aws/nginx/nginx:perl
RUN apk update && apk upgrade && apk add nginx-mod-http-image-filter
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./site /home/site
EXPOSE 80