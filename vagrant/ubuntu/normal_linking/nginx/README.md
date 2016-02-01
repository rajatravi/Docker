1.) Create an image from docker public nginx image
  - docker build -t nginx-proxy .
2.) Run the container from this image
  - docker run --name nginx-proxy -d nginx-proxy
3.) Verify if it ran fine
  - docker inspect <container id> | grep IP
  - curl  <ip of nginx-proxy container>
