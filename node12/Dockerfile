FROM node:12.3.1

RUN apt-get update

RUN apt-get install python-dev python-pip -y

RUN easy_install --upgrade six

RUN pip install awscli

CMD ["/bin/bash"]