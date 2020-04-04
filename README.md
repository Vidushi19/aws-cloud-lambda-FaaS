# Cloud Computing - FaaS
This repository is created for the purpose of showcasing the project architecture for Continous Integration and Deployment of an application on server. Here, we are using AWS provided server (PaaS). This platform/server can be referred to in the other repository namely: .

## Technology Stack

AWS Lambda Function written in JAVA
S3 Bucket
CI/CD
JSON - for Cloudwatch Metrics
Shell scripts to start/stop the server
YML - to run the shell scripts step by step and define runtime for each step.

Lambda funciton here is used to trigger the SMS request via AWS SNS whenever CRUD operations are performed on the database.
