# Cloud-Deployed Online Bookstore Web Application

A full-stack online bookstore web application designed to provide a seamless browsing and purchasing experience for readers, while offering administrators full control over content and user interactions.  
This project demonstrates full-stack web development, backend security design, cloud deployment, and basic monitoring using AWS services.

---

## 📌 Project Overview

**Unpopular** is an online bookstore platform built for book enthusiasts and casual readers to explore, discover, and purchase books in a user-friendly environment.

The application supports multiple user roles — **guest users, registered users, and administrators** — each with tailored functionality to ensure a smooth, secure, and role-appropriate experience.

The system focuses on backend logic, secure access control, and cloud-based deployment, while maintaining a functional and user-friendly frontend for everyday usage.

---

## 🏗️ Cloud Architecture & Monitoring

- Laravel application deployed using **AWS Elastic Beanstalk** on EC2
- Relational database hosted on **AWS RDS (MySQL)**
- Static assets stored in **AWS S3**
- Application access controlled via AWS Security Groups
- Application logging and basic monitoring implemented using **AWS CloudWatch**
- **S3 lifecycle rules** configured to archive infrequently accessed assets to **S3 Glacier** for cost optimization
- Backend follows MVC architecture with role-based access control

---

## ✨ Features

### 👤 Guest Users
- Browse homepage, book listings, book detail pages, and book categories
- No account registration required to explore available content

### 👥 Registered Users
- User authentication and profile management
- Shopping cart and checkout workflow
- View purchased books in **My Books**
- Contact administrators via messaging system
- View admin responses to submitted inquiries

### 🛠️ Administrators
- Book management (add, update, delete books)
- User inquiry management via **Contact Us** system
- Inquiry status tracking (Pending, In-Progress, Completed)
- Admin profile management (password and profile details)

---

## 🧰 Tech Stack

| Layer | Technologies |
|------|-------------|
| Frontend | HTML, CSS, JavaScript (Laravel Blade Templates, Responsive Layout) |
| Backend | Laravel (PHP, MVC Architecture) |
| Database | MySQL |
| Cloud Infrastructure | AWS Elastic Beanstalk, EC2, S3, S3 Glacier, RDS, CloudWatch |
| Version Control | Git, GitHub |

---

## 🔐 Security Measures

The application implements multiple backend security mechanisms:

- User authentication using Laravel authentication system
- Role-based authorization (guest, registered user, administrator)
- Authorization **Gates** to restrict access to protected routes and admin features
- Server-side input validation for all user-submitted data
- Secure session handling and access control
- Database access restricted to the application layer

---

## 👤 My Contributions

This was a **team-based project (4 members)**.  
This repository is maintained separately to highlight my individual contributions.

My primary responsibilities included:

- Backend logic implementation using Laravel
- User authentication and authorization using roles and gates
- Secure access control for admin and user-specific features
- Purchasing workflow design and implementation:
  - Add books to shopping cart
  - Checkout process (payment simulation without external gateway)
  - Order completion and purchased book display
- Database integration and backend validation
- Cloud deployment and configuration on AWS:
  - Application deployment via Elastic Beanstalk
  - EC2 environment configuration
  - RDS database setup
  - S3 static asset storage
  - CloudWatch monitoring and log inspection
  - S3 lifecycle configuration for Glacier archival

> Cloud resources are currently disabled to avoid unnecessary operational costs.

---

## 📦 Project Status

- Previously deployed on AWS cloud infrastructure  
- Cloud services are currently offline to avoid unnecessary operational costs

---

## 🚀 Future Improvements

- Improve frontend UI/UX
- Integrate a real payment gateway
- Implement CI/CD pipeline for automated deployment

---

## 📝 Notes

This project is part of my personal portfolio to demonstrate full-stack web development, backend security design, cloud deployment, monitoring, and cost-awareness experience.
