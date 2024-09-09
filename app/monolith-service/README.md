# Mysfits application

To test building and pushing the container image locally on MacOS, first install finch
and then run these these commands:

```
aws ecr get-login-password --region eu-west-1 | finch login --username AWS --password-stdin 200562504897.dkr.ecr.eu-west-1.amazonaws.com
finch build --tag 200562504897.dkr.ecr.eu-west-1.amazonaws.com/eksstack-breezyrepob8e956fd-x8goxtfoylat:latest .
finch push 200562504897.dkr.ecr.eu-west-1.amazonaws.com/eksstack-breezyrepob8e956fd-x8goxtfoylat:latest
```

Note: Do not use "latest" tag in production.
