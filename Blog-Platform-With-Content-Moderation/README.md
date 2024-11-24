# Blog Platform with Content Moderation
## Overview
This project demonstrates a serverless blog platform with integrated content moderation capabilities, leveraging AWS services. It enables users to create, manage, and moderate blog content, ensuring safe and compliant user-generated content. The platform uses AWS services for authentication, file storage, text and image moderation, and notifications.

## Key Features:
1. **User Authentication**: Secure login and registration using **AWS Cognito**.
2. **Blog Management**: CRUD operations for blog posts and metadata.
3. **File Uploads**: Media uploads (images/videos) using pre-signed URLs for **S3**.
4. **Content Moderation**: Automatic moderation of text and images using AWS Comprehend and Rekognition.
5. **Notifications**: Email notifications for flagged content using **AWS SNS**.
6. **Serverless Architecture**: Highly scalable and cost-effective solution built on **AWS Lambda, API Gateway, DynamoDB, and S3**.
