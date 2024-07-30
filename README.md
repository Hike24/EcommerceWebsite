# E-commerce MERN Stack Application

This repository contains the source code for a full-stack e-commerce application built using the MERN stack (MongoDB, Express.js, React, Node.js). The application allows users to browse and purchase products, with payment processing implemented via Stripe.

## Features

- **User Authentication**: Register, login, and manage user profiles.
- **Product Management**: View, search, and filter products.
- **Shopping Cart**: Add, remove, and manage products in the cart.
- **Order Management**: Place orders and view order history.
- **Payment Integration**: Secure payment processing using Stripe.
- **Admin Panel**: Manage products, orders, and users.

## Technologies Used

### Frontend

- **React**: A JavaScript library for building user interfaces.
- **Redux**: State management for React applications.
- **React Router**: Routing library for React.
- **Axios**: Promise-based HTTP client for the browser and Node.js.
- **Bootstrap**: Frontend framework for responsive design.

### Backend

- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing application data.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **JWT**: JSON Web Tokens for secure user authentication.
- **Stripe**: Payment processing platform.

## Installation

### Prerequisites

- Node.js and npm (Node Package Manager) installed.
- MongoDB installed and running.

### Clone the Repository

```bash
git clone https://github.com/yourusername/mern-ecommerce.git
cd mern-ecommerce
cd backend
npm install
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
npm run dev
cd ../frontend
npm install
REACT_APP_API_URL=http://localhost:5000
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
npm start
```
```
mern-ecommerce/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   ├── server.js
│   └── ...
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── actions/
│   │   ├── components/
│   │   ├── constants/
│   │   ├── reducers/
│   │   ├── screens/
│   │   ├── store/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
├── README.md
└── ...
```
