# FleetFlow

## 💻 Project Overview
FleetFlow is a full-stack logistics application designed to streamline the management of deliveries, recipients, and delivery personnel. The application consists of a Node.js API, a web app built with React.js for admin management, and a mobile app developed with React Native for delivery personnel. FleetFlow ensures efficient communication and real-time updates, making logistics management easier and more reliable.

## 🚀 Tech Stack
This project was developed using the following technologies:

### Backend
- Node.js
- Express
- PostgreSQL

### Frontend
- ReactJS
- Redux
- Styled-components

### Mobile
- React Native
- Redux
- React Navigation

### Other Technologies
- Redux-Saga
- JWT
- Axios
- AWS S3
- ESLint
- Prettier

## 📦 Key Features
- **Admin Dashboard:** Manage recipients, delivery personnel, and deliveries from a centralized web app.
- **Mobile Access:** Delivery personnel can view and update the status of their deliveries in real-time.
- **User Authentication:** Secure user authentication with JWT.
- **Responsive Design:** Enhanced user interface using Styled-components for seamless experience across devices.
- **Real-time Notifications:** Instant updates for delivery status changes and issues.
- **Progressive Web App (PWA):** Access the application offline with enhanced performance.

## 📷 Snapshots
![WhatsApp Image 2024-11-01 at 4 57 11 PM (1)](https://github.com/user-attachments/assets/49ea7963-61ce-43c0-b698-7df115d45cc9)

## 💻 My Contributions
- Developed the backend API using Node.js and Express.
- Implemented user authentication and authorization using JWT.
- Designed and developed the React.js admin dashboard and React Native mobile app.
- Integrated AWS S3 for file storage.
- Collaborated with the team to implement Redux for state management.

## 🌍 Impact
FleetFlow aims to simplify logistics management by providing a comprehensive solution that connects delivery personnel, recipients, and admins. By enhancing real-time communication and providing a user-friendly interface, FleetFlow significantly improves the efficiency of delivery operations and customer satisfaction.

## ℹ️ Getting Started
### Requirements
To run the application, you will need:
- Git
- Node.js
- Yarn

It's highly recommended to use Docker for database management.

### Setting Up Docker
```bash
# Install Redis
docker run --name redis_image -p 6379:6379 -d -t redis:alpine

# Install PostgreSQL
docker run --name postgres_image -e POSTGRES_PASSWORD=yourPassword -p 5432:5432 -d postgres

# Start Redis
docker start redis_image

# Start PostgreSQL
docker start postgres_image
Backend
### License
This project is licensed under the MIT License. See the LICENSE file for more information.
