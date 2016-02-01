For tomcat setup

1.) Run tomcat directly by pulling docker tomcat image
  - docker run -it --rm tomcat:<version>
2.) Verify if the container running tomcat
  - docker inspect <container id> | grep IP
  - curl  <ip of nginx-proxy container>:8080
