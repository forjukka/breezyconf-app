# Demo app for BreezyConf presentation

The application here is Mythical Mystits from AWS samples:

https://github.com/aws-samples/amazon-ecs-mythicalmysfits-workshop/tree/master

To keep it clean and simple, we have extracted the app itself from surrounding workshop content.
The app has dependencies on AWS resources that include Amazon S3 bucket for frontend
and Amazon DynamoDB table for NoSQL database. These are created as part of the infrastructure.
The app is built and packaged into container image and pushed to a private Amazon ECR repository 
with GitHub Actions (see .github directory for the workflow).

Since AWS recently de-emphasized AWS CodeCommit, we recommend customers to 
migrate to an external service like GitHub.
