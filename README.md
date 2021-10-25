# Terraform VPC creation with private and public subnets, plus an Internet and a NAT gateway

This demo is based on the tutorial at https://adamtheautomator.com/terraform-vpc/

It builds a VPC in AWS, with two subnets:
	- public: 10.0.0.128/26
	- private: 10.0.0.192/26

A NAT gateway allows instances in the subnets to talk to the Internet via an Internet gateway.

AWS credentials were created using the AWS CLI in ~/.aws/credentials with 'aws configure"
