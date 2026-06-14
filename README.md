


User Browser
  ↓ HTTPS
CloudFront (CDN)
  ↓
S3 Static Website (Frontend)
  ↓ HTTPS API Calls
API Gateway
  ↓
Lambda Function (Backend)
  ↓
  ├─ AWS Bedrock (AI responses) ← NEW!
  └─ S3 Memory Bucket (persistence)



![Digital Twin Architecture](Digital%20twin%20architecture.png)
