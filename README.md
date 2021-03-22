# Creating architecture in AWS using AWS CLI for webserver with CloudFront (CDN)
## The goal of the project:
Create High Availability Architecture with AWS CLI
The architecture includes- 
#### ⭕ Webserver configured on EC2 Instance
#### ⭕ Document Root(/var/www/html) made persistent by mounting on EBS Block Device.
#### ⭕ Static objects used in code such as pictures stored in S3
#### ⭕ Setting up a Content Delivery Network (CDN) using CloudFront and using the origin domain as an S3 bucket. 
#### ⭕ Finally, place the CloudFront URL on the web app code for security and low latency.
