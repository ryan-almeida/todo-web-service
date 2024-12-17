### Create an HTTP API:

- Go to the API Gateway console.
- Click Create API → Select HTTP API.
- Name the API: NotificationAPI.

### Create a POST Route:

- Add a route with the POST method and path /sendNotification.

### Integrate Lambda with the Route:

- Select the /sendNotification route.
- For integration, choose Lambda Function.
- Select < your named > Lambda function.
Deploy the API:

### Click Deploy API.
- Copy the Invoke URL (e.g., https://<api-id>.execute-api.<region>.amazonaws.com).
- Paste the URL in the HTML code for the frontend 