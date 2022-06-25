# Deployment of Image Classification Model to AWS Lambda

- Converting model to using tflite instead of tensorflow to reduce package size

- Building the lambda function to execute inference

- Building a docker image to containerize app

- Pushing image to ECR and deploying on lambda

- Configuring API Gateway to expose service as API

#### Pushing Docker Images to ECR
https://docs.aws.amazon.com/AmazonECR/latest/userguide/getting-started-cli.html