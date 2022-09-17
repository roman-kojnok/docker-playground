### docker build -t ournginx .

### docker run -d -p 80:80 --name nginx ournginx

- curl localhost:80

### To stop the container execute:
- docker stop nginx

### To remove container execute:
- docker rm nginx

### To remove image execute:
- docker rmi ournginx
