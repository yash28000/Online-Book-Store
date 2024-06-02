# Cloud Based Online Bookstore

## Overview
Welcome to the Cloud Based Online Bookstore project! This project aims to create an efficient and dependable online bookstore leveraging cloud computing technologies. Built on Microsoft Azure, this bookstore provides scalability, flexibility, and cost-effective solutions for managing books, customers, and orders.

## Table of Contents
- [Abstract](#abstract)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

## Abstract
The Cloud Based Online Bookstore revolutionizes the way people purchase books, offering a convenient and extensive selection accessible from any device at any time. It features personalized recommendations, reviews, secure payments, and quick delivery. This project explores the detailed use cases and functionalities of an e-commerce website hosted on a cloud platform like Microsoft Azure.

## Features
- **Book Categorization**: Easily browse books by various categories.
- **Recommendation System**: Personalized book recommendations based on user preferences.
- **User Reviews and Ratings**: Helps customers make informed decisions.
- **Secure Payment Gateway**: Multiple payment options for a secure checkout process.
- **Order Tracking**: Real-time tracking of book orders.
- **Administrative Panel**: Manage books, orders, and customer information efficiently.

## System Architecture
The system is designed with a centralized architecture hosted on Microsoft Azure to ensure scalability, reliability, and security. Key components include:

- **CI/CD Pipeline**: Automated pipeline using Jenkins, Docker, and Terraform for continuous integration and deployment.
- **Containerization**: Application is containerized using Docker and deployed on Azure Kubernetes Services (AKS).
- **Database**: Utilizes cloud-based database services for robust data management.

### Workflow
1. **Development**: Code changes are pushed to GitHub.
2. **CI/CD**: Jenkins triggers automated builds and tests.
3. **Dockerization**: Application is containerized and the image is pushed to a registry.
4. **Deployment**: Manually release and deploy the application on the Azure Kubernetes cluster using Terraform.

## Installation
To set up the Cloud Based Online Bookstore locally, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/cloud-bookstore.git
   cd cloud-bookstore
   Build Docker Containers:
   docker-compose build
   Run the Application:
   Copy code
   docker-compose up
   Access the Application:
   Open your browser and navigate to http://localhost:3000.
## Usage
1. **Browse Books:** Navigate through different categories and find books.
2. **Search**: Use the search bar to find specific books by title, author, or keyword.
3. **Purchase**: Add books to your cart and proceed with secure payment options.
4. **Track Orders**: View and track your book orders in real-time.

Jatin Saini
Divyansh Kohli
Jatin Kumar
Yash Singh
Shobhit Aggarwal
