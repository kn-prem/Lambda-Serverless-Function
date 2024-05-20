# Lambda-Serverless-Function
This project automates the deletion of stale EBS snapshots using an AWS Lambda function.

Create an EC2 instance from the AWS Management Console.
Create a snapshot of the volume attached to your new EC2 instance.
Create a new Lambda function with Python as the runtime.
Copy the script and past it in the code editor of lambda function created.
Test it by manually, if facing any issues with Describing Snapshots and Instances, Add those policies for this Lambda-function role which can be found in the configuration tab of Lambda Function.
Terminate the EC2 instance and run the Lambda function again to verify the snapshot is deleted.

