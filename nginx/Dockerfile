FROM nginx:latest
ADD ./nginx.conf /etc/nginx/nginx.conf
ADD ./default.conf /etc/nginx/conf.d

RUN apt-get update \
    && apt-get install -y vim \
    && rm -rf /var/lib/apt/lists/*