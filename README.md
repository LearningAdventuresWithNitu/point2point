# point2point
Simple webapp to calculate distance between 2 points using AWS

An attempt to get my hands dirty with AWS Services and Serverless Framework.

## About the app:
It is a simple webapp that takes 2 points as input and calculates the distance between them.

## How it works:
- Used various AWS services to build this. Services like AWS Amplify, AWS API Gateway, Lambda, DynamoDB and IAM were used.
- <ins>AWS Amplify:</ins> to deploy and host the app. Yet to figure out the build setting to enable automatic deployment on every commit to the repo.
- <ins>AWS API Gateway:</ins> to create a REST API to handle the request from the frontend and trigger the Lambda function.
- <ins>AWS Lambda:</ins> to calculate the distance between the given 2 points.
- <ins>AWS DynamoDB</ins>: to store the calculated distance and the time of request being made.
- <ins>AWS IAM</ins>: to create a role for the Lambda function with proper policies attached to access DynamoDB.

Working on this to get more hands on practcie experience with the services mentioned above which will also help prepare for upcoming AWS Developer certification exam. I am planning to add more features to this app in the future, refer the TODO list below. Will check things off as I make more progress and learn more about AWS.

Also, added the architechtural diagram of the app named `Point2Point.drawio.png` in the repo. It is created using [draw.io](https://app.diagrams.net/).

Thanks to ZTM Academy for the [ZTM Projects Extravaganza](https://academy.zerotomastery.io/courses/category/projects) to build projects and learn new things. This will help me hone my skills as I try to enhance these projects and add more features to them. The best way to learn is to build something and break it. I am pretty sure I will end up breaking things as I add more features along the way. On my way to build->break->learn->repeat.

## TODO:
- [ ] Link Github with Amplify to deploy the app automatically on every commit instead of manually deploying it 
- [ ] Improve UI
- [ ] Output the final result on the HTML page instead of displaying it as an alert
- [ ] Add a map to show the points and the distance between them
- [ ] Calculate the distance in miles as well
- [ ] Add proper testing
- [ ] Try to follow TDD for other projects