# Infrastructure Management and Automation
### Scheduling EBS snapshots
http://serverlesscode.com/post/lambda-schedule-ebs-snapshot-backups/
### Deleting old EBS snapshots on a recurring schedule
http://serverlesscode.com/post/lambda-schedule-ebs-snapshot-backups-2/
### Cron Jobs (Logfile cleanup, etc.)
TODO

# Logging and Monitoring
### Pushing CloudWatch to IFTTT
http://danilop.net/aws/2015/07/26/cloudwatch2ifttt/
### Splunk-enabled logging function
See blueprint splunk-logging
### Real-time call progress monitoring with Twilio
Blueprint twilio-blueprint  
https://www.twilio.com/docs/api/rest/making-calls
https://www.twilio.com/blog/2015/05/introducing-call-progress-events-flexibly-track-and-control-your-outbound-calls.html

# Mobile
### Cheat Detection (Amazon Cognito Sync Triggers)
https://mobile.awsblog.com/post/TxH3SWPR48HGAO/Using-Amazon-Cognito-and-AWS-Lambda-to-Detect-Cheating
### Build a serverless game with Lambda, S3, DynamoDB, Cognito (Computournament)
https://github.com/arafato/computournament

# Deployment and Testing
### Spawning external processes (GOLANG binaries)
http://blog.0x82.com/2014/11/24/aws-lambda-functions-in-go/
https://github.com/jasonmoo/lambda_proc
### Automatically triggered static site generation and deployment on S3 (Hugo)
https://github.com/ryansb/hugo-lambda
### Serverless Testing
See Blueprint lambda-test-harness

# Application Services
### LamdAuth: A Serverless Authentication Service
https://github.com/danilop/LambdAuth
### Triggering complex applications (such as Ray-Tracing) from Lambda
https://github.com/awslabs/lambda-ecs-worker-pattern
### A Serverless HTTP-Endoint
See Blueprint "microservice-http-endpoint"
### What is my IP?
API-Gateway + Lambda to output client's public IP
### Handling S3 Events (Thumbnailing)
http://docs.aws.amazon.com/lambda/latest/dg/walkthrough-s3-events-adminuser.html
### Handling AWS CloudTrail events (Real-time compliance checking)
http://docs.aws.amazon.com/lambda/latest/dg/wt-cloudtrail-events-adminuser.html
### Real-time Stream processing (Real-time Tweet Analysis)
https://github.com/arafato/rt-analytics
https://alestic.com/2015/11/aws-lambda-kinesis-pause-resume/
### DynamoDB Event Roll-Ups
https://www.airpair.com/lambda/posts/aws-lambda-stream-processing
### Serverless Linux-Repository Management
TODO
### Serverless Chat Application
https://github.com/cloudnative/lambda-chat

# Appendix A: Debugging Lambda
- Emulambda (Python): https://github.com/fugue/emulambda
- Lambda-Local (JavaScript/NodeJS): https://github.com/ashiina/lambda-local

# Appendix B: Lambda Configuration and Deployment
- JAWS - The Serverless Application Framework: https://github.com/jaws-framework/JAWS/
- Streambot: https://github.com/mapbox/streambot

# Appendix C: The Lambda Programming Model
- NodeJS
- Java
- Python
