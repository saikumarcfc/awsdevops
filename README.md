# awsdevops
awsdevops

It's created for my project work. What I have created here is...

Created a VPC with 2 private and 2 public subnet. 

In each of the public subnet created an Ec2 instance also had setup an application load balancer. 

Application load balancer doesthe load balance between 2 ec2 instances .

Added a NAT gateway in the public subnet from there private instance connects to the internet.

Also had setup a http server in the Ec2 instance with the default so that we can see the load balance from the application load balancer .
