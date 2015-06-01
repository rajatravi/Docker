FROM opstree/base
MAINTAINER Sandeep Rawat <sandeep@opstree.com>
RUN apt-get install -y nginx

#To make container as a pure nginx server
ENTRYPOINT ["/usr/bin/service"]

#Default parameter if nothing is passed from command line
#CMD ["nginx"]
