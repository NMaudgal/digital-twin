


graph TD
    A[User Browser] -->|HTTPS| B(CloudFront CDN)
    B --> C[S3 Static Website Frontend]
    C -->|HTTPS API Calls| D[API Gateway]
    D --> E[Lambda Function Backend]
    E --> F[AWS Bedrock AI responses - NEW!]
    E --> G[S3 Memory Bucket persistence]


![Digital Twin Architecture](Digital%20twin%20architecture.png)
