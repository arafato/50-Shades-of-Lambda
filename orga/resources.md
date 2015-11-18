# Infrastructure Management and Automation
### Scheduling EBS snapshots
http://serverlesscode.com/post/lambda-schedule-ebs-snapshot-backups/
### Deleting old EBS snapshots on a recurring schedule
http://serverlesscode.com/post/lambda-schedule-ebs-snapshot-backups-2/
### Cron Jobs (Logfile cleanup, etc.)
TODO
### Dynamic Scaling with EC2 Spot Fleet
https://aws.amazon.com/blogs/compute/dynamic-scaling-with-ec2-spot-fleet/
### Building NoSQL Database Triggers with Amazon DynamoDB and AWS Lambda
https://aws.amazon.com/blogs/compute/619/
### Email-triggered Actions with SES Incoming Emails
Email Receiving Rulesets hooked up to Lambda function  
Based on language of incoming email forward email to according native speaker in the support team (use https://github.com/mazko/jsli for language categorization)
### Dynamic GitHub Actions with AWS Lambda
https://aws.amazon.com/blogs/compute/dynamic-github-actions-with-aws-lambda/
### Building and Maintaining an Amazon S3 Metadata Index without Servers
https://blogs.aws.amazon.com/bigdata/post/Tx2YRX3Y16CVQFZ/Building-and-Maintaining-an-Amazon-S3-Metadata-Index-without-Servers
### A Zero-Administration Amazon Redshift Database Loader
https://blogs.aws.amazon.com/bigdata/post/Tx24VJ6XF1JVJAA/A-Zero-Administration-Amazon-Redshift-Database-Loader

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
### Running arbitrary executables
https://aws.amazon.com/blogs/compute/running-executables-in-aws-lambda/
#### GOLANG binaries
http://blog.0x82.com/2014/11/24/aws-lambda-functions-in-go/
https://github.com/jasonmoo/lambda_proc
#### Serverless statistics with R (R wrapped by a lambda function)
TODO
#### RUST binaries
http://julienblanchard.com/2015/rust-on-aws-lambda/
### Automatically triggered static site generation and deployment on S3 (Hugo)
https://github.com/ryansb/hugo-lambda
### A simple serverless test harness using AWS Lambda (Unit- and Load-Tests)
See Blueprint lambda-test-harness
https://aws.amazon.com/blogs/compute/serverless-testing-with-aws-lambda/
### Deploying AWS Lambda code from Amazon S3 buckets
https://aws.amazon.com/blogs/compute/new-deployment-options-for-aws-lambda/

# Application Services
### LamdAuth: A Serverless Authentication Service
https://github.com/danilop/LambdAuth
### Triggering complex applications (such as Ray-Tracing) from Lambda
https://github.com/awslabs/lambda-ecs-worker-pattern
### A Serverless HTTP-Endoint
See Blueprint "microservice-http-endpoint"
https://aws.amazon.com/blogs/compute/microservices-without-the-servers/
### What is my IP?
API-Gateway + Lambda to output client's public IP
### Handling S3 Events (Thumbnailing)
http://docs.aws.amazon.com/lambda/latest/dg/walkthrough-s3-events-adminuser.html
### Handling AWS CloudTrail events (Real-time compliance checking)
http://docs.aws.amazon.com/lambda/latest/dg/wt-cloudtrail-events-adminuser.html
### Real-time Stream processing (Real-time Tweet Analysis and Classification)
https://github.com/arafato/rt-analytics
https://alestic.com/2015/11/aws-lambda-kinesis-pause-resume/
### DynamoDB Event Roll-Ups
https://www.airpair.com/lambda/posts/aws-lambda-stream-processing
### Serverless Linux-Repository Management
TODO
### Serverless Chat Application
https://github.com/cloudnative/lambda-chat
### Serverless Hello World Service
TODO
### Hands-Free Slack: AWS Lambda meets Amazon Echo
https://aws.amazon.com/blogs/compute/slack-dictation-an-amazon-echo-and-aws-lambda-demo/
### Face recognition Service with OpenCV
https://aws.amazon.com/blogs/compute/nodejs-packages-in-lambda/

# Appendix A: Debugging Lambda
- Emulambda (Python): https://github.com/fugue/emulambda
- Lambda-Local (JavaScript/NodeJS): https://github.com/ashiina/lambda-local

# Appendix B: Lambda Configuration and CI/CD
- JAWS - The Serverless Application Framework: https://github.com/jaws-framework/JAWS/
- Streambot: https://github.com/mapbox/streambot
- Grunt plugin: https://www.npmjs.com/package/grunt-aws-lambda

# Appendix C: The Lambda Programming Model
- NodeJS
- Java
- Python
