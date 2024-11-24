# Blog Platform with Content Moderation
## Overview
This project demonstrates a serverless blog platform with integrated content moderation capabilities, leveraging AWS services. It enables users to create, manage, and moderate blog content, ensuring safe and compliant user-generated content. The platform uses AWS services for authentication, file storage, text and image moderation, and notifications.

## Key Features:
1. User Authentication: Secure login and registration using AWS Cognito.
2. Blog Management: CRUD operations for blog posts and metadata.
3. File Uploads: Media uploads (images/videos) using pre-signed URLs for S3.
4. Content Moderation: Automatic moderation of text and images using AWS Comprehend and Rekognition.
5. Notifications: Email notifications for flagged content using AWS SNS.
6. Serverless Architecture: Highly scalable and cost-effective solution built on AWS Lambda, API Gateway, DynamoDB, and S3.


## Architecture

**AWS Services Used**

1. Amazon S3: Stores static frontend files and uploaded media (images/videos).
2. Amazon Cognito: Manages user authentication and access.
3. Amazon API Gateway: Routes API requests to backend services.
4. AWS Lambda: Serverless functions for blog management, file handling, content moderation, and notifications.
5. Amazon DynamoDB: Stores blog metadata, including titles, authors, and moderation status.
6. AWS Comprehend: Analyzes blog text for inappropriate content.
7. Amazon Rekognition**: Scans uploaded images for explicit or unsafe material.
8. Amazon SNS: Sends notifications about flagged content.
9. Amazon CloudWatch: Monitors API and Lambda function logs.

![image](https://github.com/user-attachments/assets/d3a8eaef-326e-4fb0-a159-8177eb31ebde)

