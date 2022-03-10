# Autoscaling EC2

Create a VPC with cidr 10.10.0.0/16 with an autoscaling group using t2.micro instances. All instances should have apache installed on each instance with the ability to check any random IP address and be able to produce a test page. 

The instance min and max should be 2 and 5 and should have a scaling policy with cloudwatch to scale after cpu utilization is above 80%

After the autoscaling group has been created, find a stress tool to be able to stress an instance above 80% to see if your scaling policy works! 
