🚀 CloudMart Project Overview (Day 1 - Day 5)

📌 Project Summary
CloudMart is an AI-powered e-commerce platform that integrates AWS, Google Cloud (BigQuery), and Azure AI to provide product recommendations, order management, and customer support using OpenAI and Amazon Bedrock. The backend is built using AWS Lambda, DynamoDB, and Kubernetes, while the frontend is containerized and deployed in Kubernetes.

🛠️ Tools & Services Used
1️⃣ AWS Services
* AWS Lambda: Serverless functions to process product listings and order data.
* Amazon DynamoDB: NoSQL database to store products, orders, and support tickets.
* Amazon Bedrock: AI-powered recommendations and responses via Claude 3 Sonnet.
* AWS IAM: Role-based access control for Lambda, DynamoDB, and Bedrock.
* AWS ECR: Container registry for storing backend and frontend images.
* AWS CloudWatch: Log monitoring for Lambda functions.
* AWS S3: Hosting and storage of application-related files.
* AWS API Gateway: API for connecting the frontend to the backend.
* Terraform: Infrastructure as Code (IaC) for automating AWS resource deployment.
2️⃣ Google Cloud Services
* BigQuery: Stores historical order data for analytics.
* Google Cloud Service Account: Provides authentication for BigQuery operations.
* bq CLI: Command-line tool for managing BigQuery datasets and tables.
3️⃣ Azure Services
* Azure Text Analytics: Performs sentiment analysis on customer reviews and interactions.
4️⃣ Kubernetes & DevOps
* Kubernetes (EKS or K3s): Deploys backend and frontend as microservices.
* kubectl: CLI tool to manage Kubernetes deployments.
* Docker: Containerization of backend and frontend applications.
5️⃣ OpenAI API
* GPT-4o Assistant: Provides customer support via chatbot functionality.
