# Lambda-Serverless-Function
This project automates the deletion of stale EBS snapshots using an AWS Lambda function.

1. Create an EC2 instance from the AWS Management Console.
2. Create a snapshot of the volume attached to your new EC2 instance.
3. Create a new Lambda function with Python as the runtime.
4. Copy the script and past it in the code editor of lambda function created.
5. Test it by manually, if facing any issues with Describing Snapshots and Instances, Add those policies for this Lambda-function role which can be found in the configuration tab of Lambda Function.
6. Terminate the EC2 instance and run the Lambda function again to verify the snapshot is deleted.

