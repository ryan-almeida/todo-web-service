### Go to the AWS Lambda Console:

- Navigate to AWS Lambda.
- Click Create function → Author from scratch.
- Function name: NotificationHandler.
- Runtime: Choose Python 3.x.
- Click Create function.
### Add Permissions to Lambda:

- In the Lambda function page, go to Configuration → Execution role → Role name.
Attach the AmazonSNSFullAccess policy to the role.
### Write the Lambda Function Code:
- See the Lambda Function code attached 