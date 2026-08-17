# 💙 GetMeDonation

GetMeDonation is a full-stack donation platform built with **Next.js** that allows users to support animal shelters and make online donations through a secure payment flow.

The project was built to understand how a modern full-stack application works, including authentication, database operations, payment integration, API routes, and responsive UI development.

> 🚧 **Project Status:** Currently under development. The project has not been deployed yet.

## ✨ Features

* 🔐 **GitHub Authentication** using NextAuth
* 💳 **Razorpay Payment Integration**
* 🗄️ **MongoDB Database** for storing users and payment information
* 👤 User authentication and protected features
* 🐾 Donation support for animal shelters
* 📱 Responsive user interface
* 🎨 Modern UI built with Tailwind CSS
* 🔄 Server-side and client-side functionality using Next.js
* 🧩 Reusable React components
* 🔒 Environment variables for sensitive configuration

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* Tailwind CSS
* JavaScript

### Backend

* Next.js API Routes
* Node.js
* MongoDB
* Mongoose

### Authentication & Payments

* NextAuth
* GitHub OAuth
* Razorpay

## 📂 Project Structure

```text
GetMeDonation/
├── app/
│   ├── api/
│   ├── components/
│   ├── login/
│   ├── payment/
│   └── ...
├── models/
├── public/
├── .env.local
├── package.json
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the project

```bash
cd GetMeDonation
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env.local` file in the root directory and add the required environment variables.

Example:

```env
MONGODB_URI=your_mongodb_connection_string

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret

GITHUB_ID=your_github_client_id
GITHUB_SECRET=your_github_client_secret

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

> **Note:** Never commit your `.env.local` file or expose your API keys and secrets publicly.

### 5. Run the development server

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:3000
```

## 💳 Payment Flow

The application uses **Razorpay** to process donations.

The general payment flow is:

```text
User
  ↓
Donation Form
  ↓
Create Payment Order
  ↓
Razorpay Checkout
  ↓
Payment
  ↓
Payment Verification
  ↓
Store Payment Information
  ↓
Donation Completed
```

## 🔐 Authentication

Authentication is implemented using **NextAuth** with GitHub OAuth.

Authenticated users can access features that require a logged-in session, while protected routes prevent unauthorized access.

## 🗄️ Database

The application uses **MongoDB** as its database and **Mongoose** for interacting with MongoDB.

The database stores information such as:

* User details
* Usernames
* Payment information
* Donation details
* Messages associated with donations

## 🎯 What I Learned

While building this project, I worked with:

* Next.js App Router
* React components and hooks
* NextAuth authentication
* GitHub OAuth
* MongoDB and Mongoose
* API routes
* Razorpay payment integration
* Payment verification
* Environment variables
* Tailwind CSS
* Responsive design
* Server-side and client-side concepts
* Protected routes and sessions

## 🚧 Future Improvements

Some improvements planned for the project include:

* [ ] Deploy the application
* [ ] Improve payment and transaction handling
* [ ] Add an admin dashboard
* [ ] Add better donation analytics
* [ ] Improve error handling
* [ ] Add email notifications
* [ ] Improve accessibility
* [ ] Add more shelter-related features

## 📌 Project Status

This project is currently being developed as a personal full-stack web development project.

The application is functional in a local development environment, but **has not been deployed yet**.

## 👨‍💻 Author

**Yash Sharma**

BCA Graduate | Full-Stack Web Development Learner

Built using **Next.js, React, MongoDB, NextAuth, Razorpay and Tailwind CSS**.

