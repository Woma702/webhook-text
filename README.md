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


Major Job Duties and Responsibilities:
•	Analyze existing cloud architecture then recommend and design improvements
•	Deliver technical solutions for projects leveraging agile project management methodologies
•	Develop cloud architecture strategies that can be consistently applied across the enterprise
•	Develop and maintain enterprise standards for cloud ecosystem architecture
•	Identify technical risk in projects and develop strategies to alleviate it
•	Communicate technical cloud architecture direction and how it relates to business objectives to all levels of the organization through documentation, training, and awareness
•	Lead design discussions with appropriate personnel to define goals and objectives of business applications in the cloud
•	Help to clarify, identify, and track requirements and project issues and escalate to immediate manager where required
•	Act as primary point of contact for the Global Architecture team with Cloud Operations and Front Office Delivery teams within Allegion IT
•	Develop and maintain a thorough knowledge of multiple Allegion business functions and how the system and procedures that support these functions interrelate to develop/support cloud architecture implementations
•	Accountable for building and maintaining build and deployment pipelines including tools used to automate quality and security within those pipelines.
•	Design, develop, and integrate/automate solutions for CI/CD pipeline using various cloud technologies.
•	Collaborate with various IT teams to enable best implementation of Allegion solutions in cloud environments
