# AWS Community Day Bengaluru - Blogathon

## Disclaimer

**This is not a step-by-step guide, just my trade-off analysis on using Amazon Cognito to provide social login for your app and some pitfalls I found in my experience.**

## Introduction

In this article, I'll show you my serverless solution to add social identity providers as a login option for web and mobile applications, based on managed services and native integrations, and how I mitigated some issues I encountered.

## Blog Link

**[Read the full blog here](#)**

## Overview

This project demonstrates how to integrate **Amazon Cognito** with social identity providers like **Google, Facebook, and Apple** for authentication in your web and mobile applications.

### Features

- **Amazon Cognito Integration**
  - Social login support (Google, Facebook, Apple, etc.)
  - Secure user authentication
  - Session management
  - User attribute customization
- **Serverless Architecture**
  - No backend management required
  - Fully managed AWS services
- **React.js & MobX for Frontend**
  - Modern UI framework
  - State management with MobX
  - Responsive and scalable design

## Setup Instructions

### 1. Clone this repository
```sh
 git clone https://github.com/your-repo/aws-cognito-auth
 cd aws-cognito-auth
```

### 2. Configure AWS Cognito
- Go to AWS Console → Cognito → User Pools.
- Create a **User Pool** with social identity provider integration.
- Copy **User Pool ID** and **App Client ID** into `.env` file.

### 3. Install dependencies
```sh
 yarn install
```

### 4. Run the application
```sh
 yarn start
```

## Screenshots

![Screenshot](https://user-images.githubusercontent.com/2158187/29740369-866d9832-8a87-11e7-9f1e-e4cd77a54df4.png)

![Screenshot](https://user-images.githubusercontent.com/2158187/29740368-865b95ba-8a87-11e7-8563-dfeaa4b10e75.png)

## Conclusion

Using **Amazon Cognito** simplifies authentication while enabling seamless social login integration. However, understanding the trade-offs, such as potential customization limitations, helps optimize implementation for real-world applications.

For a detailed analysis, **[read the full blog here](#)** 🚀
