    $ docker build -t nginx .
    $ docker run -d -p 80:80 -v /var/www:/var/www --name nginx nginx:latest
