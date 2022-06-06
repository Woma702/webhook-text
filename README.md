# webhook-text
Testing the webhook 
Prerequisites:
1.	Ansible needs to be installed in master.
2.	Connection between Master and Host needs to be set through ssh. For more information refer to the Ansible Installation Documentation.


#!/bin/bash

# install dependencies
yum -y group install "Development Tools"
yum -y install \
        bzip2-devel.x86_64 \
        java-11-amazon-corretto-headless \
        libffi-devel \
        ncurses-devel \
        openssl-devel \
        python3 \
        readline-devel.x86_64 \
        sqlite-devel.x86_64 \
        zlib-devel

# install the elastic beanstalk CLI
curl -O https://bootstrap.pypa.io/get-pip.py
/usr/bin/python3 get-pip.py
/usr/local/bin/pip3 install awsebcli
