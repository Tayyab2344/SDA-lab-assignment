# Serverless State Management with AWS Lambda

This project demonstrates stateful applications using AWS Lambda and DynamoDB, addressing cold start latency, state persistence, and debugging challenges.

## Features:
- **Cold Start Mitigation**: Keep Lambda warm using scheduled CloudWatch events.
- **State Management**: Store and retrieve state in DynamoDB.
- **Monitoring**: Logs to CloudWatch and traces with AWS X-Ray.
