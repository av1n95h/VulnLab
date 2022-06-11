docker build . -t jboss
docker run -d -p 8080:8080 jboss:latest
