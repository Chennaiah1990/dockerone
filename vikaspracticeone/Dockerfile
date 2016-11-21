# hai this is my jenkins installation process made by  vikas
FROM ubuntu
MAINTAINER chennybirru@gmail.com
RUN -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -
RUN -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
RUN apt-get update
RUN apt-get install jenkins
CMD ["echo","hai this vikas jenkins installation"]
