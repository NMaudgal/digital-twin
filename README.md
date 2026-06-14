
# **AI Digital Twin**


In this project, I implemented a complete CI/CD and DevOps pipeline for an AI Digital Twin platform on AWS.
I used GitHub Actions to automate deployments across Dev, Test, and Production environments. 
Infrastructure was managed entirely using Terraform with remote state stored securely in S3 and DynamoDB locking.
For secure AWS authentication, I implemented GitHub OIDC federation instead of static access keys, following modern cloud security best practices.
The architecture includes CloudFront and S3 for frontend hosting, API Gateway and Lambda for backend APIs, and AWS Bedrock for AI inference. Conversation memory is persisted in S3.
The pipeline supports automated deployment, environment isolation, infrastructure teardown, CloudFront cache invalidation, and centralized monitoring through CloudWatch.
Overall, this project demonstrates production-grade Infrastructure as Code, CI/CD automation, multi-environment management, and secure serverless AI deployment on AWS.



![Architecture Twin](Architecture-twin.png)

![Digital Twin Architecture](Digital%20twin%20architecture.png)


