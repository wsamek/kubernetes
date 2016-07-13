FROM ubuntu:xenial

RUN apt-get -y update && apt-get install -y python python-dev python-pip && pip install --upgrade pip && pip install python-openstackclient
RUN apt-get install -y curl
RUN pip install -U --force 'python-openstackclient==2.4.0'
RUN pip install -U --force 'python-swiftclient==3.0.0'
RUN pip install -U --force 'python-glanceclient==2.0.0'
RUN pip install -U --force 'python-novaclient==3.4.0'
RUN pip install python-heatclient

