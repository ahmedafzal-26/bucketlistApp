# Bucket List Tracker App

A full-stack web application built with AWS Amplify that allows users to create and manage their bucket list items. Users can add, update, and delete items on their bucket list, as well as upload images associated with each item.

## Features

- User authentication and authorization
- CRUD operations for bucket list items
- Image upload capability for bucket list items
- Responsive user interface
- Continuous Integration/Continuous Deployment (CI/CD) pipeline

## Technologies Used

- Frontend:
  - React.js
  - AWS Amplify UI Components
  - CSS for styling
- Backend:
  - AWS Amplify
  - Authentication services
  - Data storage
  - File storage for images

## Prerequisites

- Node.js (latest version)
- Git
- AWS Account
- GitHub Account


## AWS Amplify Setup

1. Sign in to AWS Management Console
2. Navigate to AWS Amplify
3. Connect your GitHub repository
4. Follow the deployment steps in the Amplify console

## Backend Configuration

The backend includes:
- Authentication setup with default settings
- Data storage for bucket list items
- File storage for image uploads

Key configuration files:
- `amplify/data/resource.ts` - Schema definition
- `amplify/backend.ts` - Backend configuration

## Deployment

The application is automatically deployed through AWS Amplify's CI/CD pipeline. Any changes pushed to the main branch will trigger a new deployment.

Challenges Faced During Development
During the development of this application, several significant challenges were encountered:

Git Repository Issues

Encountered difficulties when attempting to push code to the GitHub repository
Initial pushes to the main branch were problematic
Git authentication and authorization presented obstacles


SSH Key Configuration

Setting up the Git passphrase proved challenging
SSH key generation and management required additional configuration
Authentication with GitHub via SSH needed multiple attempts


AWS Amplify Cloud Sandbox

Creating and configuring the cloud sandbox environment presented several hurdles
Faced credential errors when attempting to create the sandbox
Authentication token issues occurred during sandbox initialization

## Application Structure

```
bucketlistapp/
├── src/
│   ├── App.jsx
│   ├── index.css
│   └── ...
├── amplify/
│   ├── data/
│   │   └── resource.ts
│   └── backend.ts
└── ...
```

## Development Workflow

1. Test changes using `npm run dev`
2. Commit and push changes to GitHub
3. AWS Amplify automatically deploys updates
