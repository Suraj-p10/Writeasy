# Writeasy - Blog Generation App

![Writeasy Banner](assets/banner.png) <!-- Replace with an appropriate banner or remove this line -->

Writeasy is an end-to-end **blog generation app** leveraging the power of **AWS Cloud Services** and **Meta Llama 3 8B**. This application demonstrates the integration of serverless architecture, API Gateway, and scalable storage solutions to generate high-quality blog content seamlessly.

---

## 🌟 Features
- **AI-Generated Blogs:** Harness Meta Llama 3 8B for intelligent and creative content generation.
- **Serverless Architecture:** Utilize AWS Lambda for efficient, on-demand processing.
- **API-Driven Workflow:** Manage blog generation using APIs via AWS API Gateway.
- **Scalable Storage:** Store and manage generated content with AWS S3.
- **Postman Integration:** Test and trigger API requests effortlessly.

---

## 🛠️ Technologies Used
- **AWS Bedrock**: To manage foundational AI models.
- **AWS Lambda**: For serverless compute to process requests.
- **AWS S3**: To securely store generated blogs.
- **AWS API Gateway**: For managing RESTful API endpoints.
- **Postman**: For API testing and triggering requests.
- **Meta Llama 3 8B**: As the Large Language Model for content generation.

---

## 🚀 Architecture Overview

1. **API Gateway**: Accepts API requests for blog generation.
2. **Lambda Function**: Processes requests and generates content using Meta Llama 3 8B.
3. **AWS S3**: Stores generated content for retrieval and scalability.

![Architecture Diagram](assets/architecture.png) <!-- Add an architecture diagram here -->

---

## 🔧 Setup and Installation

### Prerequisites
- AWS account with access to Bedrock, Lambda, S3, and API Gateway.
- Postman installed for API testing.
- Python environment for Lambda function deployment.

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Suraj-p10/Writeasy.git
   cd Writeasy
