# Deploy-a-high-availability-web-app-using-CloudFormation
Cloud Formation templates for deploying a website

The URL to the Load Balancer for the Udagram Web Application is: http://udagr-applb-152rl66df49sd-1404616830.us-east-1.elb.amazonaws.com/

Reason for using t2 instead of recommended t3.small is because the t3.small instance type meets the two vCPU requirement bot does not meet the 4 Gb RAM requirement
But on the other had the t.medium instance type meets both requirements.
