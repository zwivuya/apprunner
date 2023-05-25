FROM --platform=linux/amd64 php:8.1.0-fpm
WORKDIR /app
COPY ./index.php ./
COPY ./apprunner.yaml ./
EXPOSE 3000
CMD ["php","-S", "0.0.0.0:3000"]
