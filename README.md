# IAC-Udacity-Project2
### Scenario 
- Your company is creating an Instagram clone called Udagram.
- Developers want to deploy a new application to the AWS infrastructure.  
- You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.  
- This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.  
- 
- Optional - To add more challenge to the project, once the project is completed, you can try deploying sample website files located in a public S3 Bucket to the Apache Web Server running on an EC2 instance. Though, it is not the part of the project rubric.

### solution: (This link will be unreachable now as the Stack was Deleted.)
- loadbalancer DNS: http://Udaci-WebSe-GUR26G7DO26E-1475915719.us-east-1.elb.amazonaws.com
### To run my script use this command 
- Bash command: aws cloudformation create-stack --stack-name Udacity-Project2 --region us-east-1 --template-body file://IAC-Udacity-Project2.yml --parameters file://IAC-Udacity-Project2-params.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM"
