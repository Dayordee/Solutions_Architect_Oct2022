# Working with EC2 instance using the AWS CLI / Programmable access

Tasks:

1. Using your default vpc, find the public subnet
2. Create a security group
3. Launch an instance with a web server with termination protection enabled
4. Monitor Your EC2 instance; view the types of metrics that are collected for an EC2 instance
5. Modify the security group that your web server is using to allow HTTP access
6. Resize your Amazon EC2 instance to scale


Guide
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/terminating-instances.html


https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-resize.html

1. through my VPC  ![](../../images/Vpc.png) I found my  subnet
![](../../images/subnets.png)


2. I created a security group
![](../../images/newSG.png)

3. I Launch an instance with a web server with termination protection enabled
![](../../images/launch%20instance.png)
![](../../images/terminator.png)

4.![](../../images/Screenshot%20(658).png) and i viewed the metrics
![](../../images/metric.png)

5. I modified the security group with HTTP acces 
![](../../images/modify.png)

6.  I enable auto scaling group for my instance
![](../../images/Screenshot%20(660).png)
![](../../images/Screenshot%20(662).png)