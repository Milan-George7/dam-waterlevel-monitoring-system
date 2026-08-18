# Dam Water Level Monitoring System

• Developed a full-stack React and Node.js application for monitoring dam water levels, operator management, authentication, and system settings.

• Deployed the production application on AWS EC2 using Nginx as a reverse proxy and PM2 for persistent Node.js process management.

• Integrated MongoDB Atlas for cloud database persistence and configured secure EC2-to-Atlas connectivity.

## 🚀 Live Deployment

The application is deployed on AWS EC2 using Nginx as a reverse proxy, PM2 for backend process management, and MongoDB Atlas for cloud database hosting.

> The live EC2 public IP may change when the instance is stopped and restarted.

## 📌 Features

- Admin authentication
- Secure user authentication using JWT
- Dam water-level monitoring
- Water-level record management
- Operator management
- System settings management
- RESTful backend API
- MongoDB-based data persistence
- Responsive React frontend
- Production deployment on AWS EC2

## 🛠️ Tech Stack

### Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- Axios
- React Router

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- Express Validator
- CORS
- dotenv

### Cloud & Deployment

- AWS EC2
- Ubuntu
- Nginx
- PM2
- MongoDB Atlas
- Git / GitHub

## 🏗️ Architecture

```text
                         Internet
                            │
                            ▼
                     AWS EC2 Instance
                            │
                            ▼
                       Nginx :80
                      /          \
                     /            \
                    ▼              ▼
             React Frontend      /api
                                   │
                                   ▼
                            Node.js + Express
                              PM2 :5000
                                   │
                                   ▼
                            MongoDB Atlas
