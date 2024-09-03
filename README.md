# Demo app for BreezyConf presentation

The application here is Mythical Mystits from AWS samples:

https://github.com/aws-samples/amazon-ecs-mythicalmysfits-workshop/tree/master

To keep it clean and simple, we have extracted the app itself from surrounding workshop content.
This repo also contains AWS dependencies for the app, which include Amazon S3 bucket for frontend
and Amazon DynamoDB table for backend NoSQL database. The app is packaged as container image
and pushed to a private Amazon ECR repository with GitHub Actions. Since AWS recently de-emphasized
AWS CodeCommit, we recommend customers to migrate to GitHub (or Gitlab).
