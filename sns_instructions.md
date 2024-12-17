### Create an SNS Topic:

- Go to the Amazon SNS console.
- Click Topics, then Create topic.
- Choose Standard as the topic type.
- Set the topic name, e.g., NotificationSystemTopic.
- Click Create topic.

### Add Subscriptions:

- Select the topic created above.
- Click Create subscription for the first recipient:
    - Protocol: Email
    - Endpoint: Enter the predefined email address.
- Create another subscription for the phone number:
    - Protocol: SMS
    - Endpoint: Enter the phone number (e.g., +1234567890 with country code).
- Confirm the email subscription by clicking the verification link sent to the email address.
### Copy the SNS Topic ARN:

- Copy the Topic ARN (e.g., arn:aws:sns:<region>:<account-id>:NotificationSystemTopic) for use in the Lambda function.