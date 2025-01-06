# Learning Management System (LMS) 

This project is an enterprise-grade full-stack Learning Management Application built using modern technologies such as **Next.js**, **Node.js**, **AWS**, **Docker**, and **Clerk**. The application is designed to be scalable, secure, and efficient, offering an optimal learning experience with features like course management, billing, and authentication.

## Demo
You can explore the demo of the Learning Management System here:  
[Demo Link]

## Completed Code
Access the full code repository here:  
[GitHub Repository](https://github.com/e-nk/learning-mgmt)

## Diagrams and Assets
- Diagrams: [View Diagrams](https://miro.com/app/board/uXjVLDSd2p0=/)

---

## Table of Contents

1. [Description](#description)
2. [Tech Stack](#tech-stack)
3. [Frontend Setup](#frontend-setup)
4. [Backend Setup](#backend-setup)
5. [Authentication with Clerk](#authentication-with-clerk)
6. [AWS Setup](#aws-setup)
7. [Docker Setup](#docker-setup)
8. [Deployment](#deployment)
9. [Links to Tools and Resources](#links-to-tools-and-resources)

---

## Description

This tutorial covers how to build a **Learning Management System** (LMS) with **Next.js**, **Node.js**, and **AWS** services. The application consists of a frontend, backend, and various integrations that help create a fully-fledged scalable LMS. This project uses **Clerk** for authentication, **DynamoDB** for database storage, **S3** for file storage, and **AWS Lambda** for serverless functions.

### Features:
- **Frontend**: Next.js, Redux Toolkit, Tailwind CSS, Shadcn, TypeScript, Framer Motion, React Hook Form, Zod, and Stripe for managing payments.
- **Backend**: Node.js, Express.js, Docker, AWS Lambda, API Gateway, DynamoDB, S3, CloudFront.
- **Authentication**: Simplified using Clerk.
- **Hosting**: The frontend is hosted on Vercel.

---

## Tech Stack

### Frontend
- **Next.js**: A React framework for building static and dynamic web applications.
- **Redux Toolkit**: For state management.
- **Tailwind CSS**: For utility-first styling.
- **Shadcn UI**: UI components for building beautiful user interfaces.
- **React Hook Form**: For handling form validation.
- **Zod**: For schema validation.
- **Framer Motion**: For animations.
- **Stripe**: For managing payments and subscriptions.

### Backend
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web application framework for Node.js.
- **DynamoDB**: AWS's NoSQL database service.
- **AWS Lambda**: Serverless compute service.
- **API Gateway**: To expose backend APIs.
- **S3 & CloudFront**: For file storage and content delivery.

### Authentication
- **Clerk**: Simplified authentication and user management.

### Hosting and Deployment
- **Frontend**: Hosted on Vercel.
- **Backend**: Hosted on AWS Lambda with API Gateway.

---

## Frontend Setup

### Install Dependencies
1. Clone the repository:
   ```bash
   git clone git@github.com:e-nk/learning-mgmt.git
   cd learning-mgmt
2. Install dependencies:
   ```bash
   npm install --legacy-peer-deps
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Visit http://localhost:3000 in your browser to see the app in action.

### Key Frontend Libraries and Tools:
1. [Shadcn UI](https://ui.shadcn.com/docs)
2. [React Hook Form](https://react-hook-form.com/)
3. [Zod](https://github.com/colinhacks/zod)
4. [Stripe](https://docs.stripe.com/get-started)

---

### Backend

1. Install the backend dependencies:

   ```bash
	 npm install --legacy-peer-deps 
2. Configure AWS credentials using the AWS CLI:
   ```bash
   aws configure
   ```
3. Set up local DynamoDB (for local development):
	- [DynamoDB Documentation](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html)
4. For local testing, use Postman to interact with the APIs:
   - [Download Postman](https://www.postman.com/downloads/)

---

### Authentication with Clerk
1. Sign up for a Clerk account:
   - [Clerk Website](https://clerk.dev/)
	- Integrate Clerk in the frontend and backend as per the provided tutorial.
2. Use Clerk's pre-built UI components and hooks to handle authentication flows.

---

### AWS Setup
1. #### AWS IAM: Set up IAM roles for security.
   - [IAM Documentation](https://aws.amazon.com/iam/)
2. #### AWS ECR: Use Elastic Container Registry for storing Docker images.
   - [ECR Documentation](https://aws.amazon.com/ecr/)
3. #### AWS Lambda: Host backend APIs and services in a serverless manner.
   - [Lambda Documentation](https://aws.amazon.com/lambda/)
4. #### API Gateway: Expose Lambda functions via RESTful APIs.
   - [API Gateway Documentation](https://aws.amazon.com/api-gateway/)
5. #### AWS S3 & CloudFront: Store and deliver content globally via S3 and CloudFront.
   - [S3 Documentation](https://aws.amazon.com/s3/)
	- [CloudFront Documentation](https://aws.amazon.com/cloudfront/)

---

### Docker Setup
1. Install Docker:
   - [Docker Installation](https://docs.docker.com/get-docker/)

2. Docker Commands:
   - Build the Docker images: 

	    ```bash
			docker build -t learning-mgmt . 
   - Run the Docker containers: 

      ```bash
      docker run -p 3000:3000 learning-mgmt
      ```

---

## Deployment
### Frontend Deployment on Vercel
1. Push your frontend code to GitHub.
2. Connect your GitHub repository to Vercel and deploy.
### Backend Deployment on AWS Lambda
1. Deploy backend functions to Lambda using AWS CLI or the Serverless Framework.

---

## Links to Tools and Resources
- [Clerk Website](https://clerk.dev/)
- [Shadcn UI](https://ui.shadcn.com/docs)
- [Stripe](https://docs.stripe.com/get-started)
- [AWS Documentation](https://aws.amazon.com/)
- [Docker](https://www.docker.com/)

---

## Author
This project was made with ❤️ and ☕ by:

[Enock](https://github.com/e-nk)
