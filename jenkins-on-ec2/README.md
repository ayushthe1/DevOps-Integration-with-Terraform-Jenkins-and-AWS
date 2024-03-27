# jenkins-on-ec2

This directory contains terraform code to setup infrastructure on AWS.
The main idea is to create a ec2 instance in a public subnet and install a jenkins server on it. Security groups, route table , load balancer, certificate manager is also configured. 

After the setup, traffic to https://jenkins.ayushsharma.co.in is routed to the ec2 instance by AWS Route 53.