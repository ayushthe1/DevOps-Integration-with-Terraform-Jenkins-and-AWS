## A project to set up AWS infrastructure using Terraform and then use Jenkins to build a CICD pipeline which will host a simple flask application on AWS.

# flask-app-aws

This directory contains code to setup infrasturce on AWS as shown in the figure below. The jenkinsfile(which contains code to setup infrastructure) present in this directory is used by the jenkins server running on the ec2 instance in the eu-west-1 region defined in the directory `jenskins-on-ec2`. 

After the setup, traffic to https://ayushsharma.co.in is routed to the ec2 instance which contains the flask app