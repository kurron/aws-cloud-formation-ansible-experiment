# Overview
This project is an experiment to see how a [CloudFormation](https://aws.amazon.com/cloudformation/) created stack 
can be provisioned by [Ansible](https://www.ansible.com/) as it is constructed.  An example use case is to create
an [LVM](https://en.wikipedia.org/wiki/Logical_Volume_Manager_(Linux)) partition from the attached 
[EBS](https://aws.amazon.com/ebs/) volumes and format it for use.

1. create a CloudFormation template the creates an EC2 instance and EBS store
1. run the template
1. have the template execute a simble Bash command
1. copy a script from S3 into the instance
1. run the script
1. refined the script to run Ansible

# Prerequisites
* TODO 

# Building
TODO

# Installation
TODO

# Tips and Tricks
TODO

# Troubleshooting
TODO

# License and Credits
This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

