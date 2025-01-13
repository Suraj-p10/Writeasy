# Writeasy
Blog Generation App using AWS
# Blog Generation App using AWS Cloud

![App Banner](path/to/your/image.png) <!-- Replace with the actual path to your PNG file -->

## Overview
This **Blog Generation App** leverages AWS Cloud services and Meta Llama 3 8B to generate high-quality blog content seamlessly. The app demonstrates the power of serverless architecture, API integrations, and scalable storage using AWS.

## Features
- **Blog Content Generation:** Automatically generate blog articles using Meta Llama 3 8B.
- **Serverless Architecture:** Built using AWS Lambda, S3, and API Gateway.
- **API Integration:** Trigger content generation with ease using Postman.
- **Scalable Storage:** Generated content is stored in AWS S3 for easy access and scalability.

## Technologies Used
- **AWS Bedrock**: For deploying and managing foundational models.
- **AWS S3**: For storing generated content securely and scalably.
- **AWS Lambda**: For serverless compute to generate blogs.
- **AWS API Gateway**: To create and manage API endpoints.
- **Postman**: For sending API requests and testing endpoints.
- **Meta Llama 3 8B**: LLM for generating high-quality blog content.

## Architecture
1. **API Request**: Postman sends API requests via AWS API Gateway.
2. **Lambda Function**: AWS Lambda processes the request and uses Meta Llama 3 8B to generate content.
3. **Content Storage**: The generated blog content is stored in AWS S3 for future access.

## Setup and Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/blog-generation-app.git
   cd blog-generation-app

