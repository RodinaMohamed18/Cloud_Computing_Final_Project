# ☁ Smart File Sharing System — Cloud Computing Final Project

A modern, secure, and scalable file-sharing web application powered by *AWS*.  
This project is built as part of the Cloud Computing course and demonstrates full-stack cloud deployment using real-world AWS services.

---

## 🚀 Overview

*Smart File Sharing System* is a cloud-native web app that enables users to seamlessly upload, download, and manage their files through a sleek browser interface. It leverages core AWS services to deliver performance, scalability, and security.

Built with:
- *Flask Python* backend hosted on EC2  
- *Amazon S3* for durable and scalable file storage  
- *IAM* for secure access control  
- *VPC* for private networking  
- *Route 53* for domain management

---

## ⚙ Key Features

- Upload, download, and delete files in the cloud  
- Secure communication between backend and storage  
- IAM Role-based permission control (no hardcoded credentials)  
- Fully isolated network using VPC & security groups  
- Real DNS routing with Route 53  
- Simple UI with fast performance  

---

## 🧱 Architecture Diagram

![Architecture](./architecture.png)

> A web user communicates with a backend server hosted on EC2. That server interacts securely with S3 buckets inside a protected VPC, using IAM roles. Route 53 handles DNS routing for public access.

---

## ☁ AWS Services Used

| Service     | Purpose                                 |
|-------------|-----------------------------------------|
| *EC2*     | Hosts the backend application           |
| *S3*      | Stores user-uploaded files              |
| *IAM*     | Controls access between services        |
| *VPC*     | Provides secure private networking      |
| *Route 53*| Connects the system to a custom domain  |

---

## 🧪 How It Works

1. Users interact with a simple web form to upload or manage files.
2. Requests are sent to a Node.js/Express server running on an EC2 instance.
3. The server uses IAM roles to securely connect to an S3 bucket.
4. All resources operate within a secured VPC.
5. Domain access is routed via Route 53 for a professional look.

---

## 👨‍💻 Project Team

- *Farah Walid* – AWS Account Setup & Documentation  
- *Nour Essam* – Web App Development  
- *Basmala Hossam El-Din* – EC2 & IAM Setup  
- *Rodina Mohamed* – S3 & File Handling  
- *Mariam Ahmed* – VPC Configuration & Testing  


---

## 🔗 Live Demo

[*Click here to try the live app*](http://34.228.158.194)

---

- *Drive Link:*
https://drive.google.com/file/d/1A5fK4JQgDUH7oINnupxYirtG9nonPiql/view?usp=sharing

---

## ✅ Final Thoughts

This project demonstrates a real-world application of cloud computing concepts, integrating key AWS services to build a secure and efficient platform for file management. It’s lightweight, scalable, and ready for future enhancements.

---
