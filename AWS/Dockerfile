FROM amazonlinux
MAINTAINER woochul <crepers12@hanmail.net>

RUN yum update -y
RUN yum install tar -y
RUN yum install zip -y
RUN curl --silent --location https://rpm.nodesource.com/setup_8.x | bash -
RUN yum -y install nodejs
RUN npm update -y

VOLUME ["/data"]

#docker build -t awslinux .
#docker run -i -t --name aws -v /Users/woochuljung/work/DockerFiles/data:/data awslinux /bin/bash
#zip -r promise nodejs