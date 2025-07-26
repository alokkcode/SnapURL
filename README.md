# Project Overview:

*SnapURL is a sleek and powerful URL shortening solution designed to transform long, unwieldy web addresses into short, memorable links. Built with a modern full-stack architecture, it not only shortens URLs but also provides valuable analytics and secure user management. SnapURL is the perfect tool for marketers, developers, and anyone looking to clean up their links and track their engagement with ease and precision.*

-----

## Tech Stack :

\<img src="[https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg](https://www.google.com/search?q=https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg)" height="50" /\> \<img src="[https://raw.githubusercontent.com/devicons/devicon/master/icons/vitejs/vitejs-original.svg](https://www.google.com/search?q=https://raw.githubusercontent.com/devicons/devicon/master/icons/vitejs/vitejs-original.svg)" height="50" /\> \<img src="[https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg](https://www.google.com/search?q=https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg)" height="50" /\> \<img src="[https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg](https://www.google.com/search?q=https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg)" height="50" /\> \<img src="[https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg](https://www.google.com/search?q=https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg)" height="50" /\>

-----

## Core Functionality:

At the heart of SnapURL is a robust system designed for speed, security, and analytics. Here’s a step-by-step breakdown of its operation:

-----

### URL Shortening & Redirection:

When a user submits a long URL, the Node.js and Express backend generates a unique, short identifier. This new short link is stored in the MongoDB database, mapped to the original URL. When anyone visits the short link, the server performs an instantaneous lookup and redirects them to the original destination seamlessly.

-----

### Secure User Management:

To protect user data and provide personalized analytics, SnapURL uses a secure authentication system. User registration and login are managed via JWT (JSON Web Tokens). Once authenticated, a user's session is secured, ensuring that only they can manage their links and view their private analytics dashboards.

-----

### Insightful Analytics:

SnapURL doesn’t just shorten links—it provides intelligence. For every link created, the system tracks vital metrics such as the total number of clicks and the creation timestamp. This data is presented to the user in a clean, intuitive dashboard, allowing them to measure the performance and reach of their links.

-----

## Why SnapURL Stands Out:

  - **Simplicity & Speed**: Instantly transform long, cumbersome URLs into clean and shareable links with a fast, responsive interface built on React and Vite.
  - **Data-Driven Insights**: Go beyond shortening with a built-in analytics engine that tracks click counts, helping you understand your audience engagement.
  - **Secure & Private**: With JWT-based authentication, user accounts and link data are protected, ensuring that your information remains private and secure.
  - **Modern & Scalable**: Built on a robust stack (Node.js, Express, MongoDB), SnapURL is designed to be reliable and scalable for both personal and enterprise use.

-----

### Conclusion:

*SnapURL is more than just a utility; it's a complete link management tool. By combining a fast and intuitive user experience with powerful analytics and robust security, it provides a comprehensive solution for anyone needing to optimize their digital presence. Whether you're sharing content on social media or in marketing campaigns, SnapURL gives you the control and insight you need to succeed.*

-----

## 📦 Prerequisites

Make sure you have the following installed on your system:

  - **Node.js** (v18+ recommended)
  - **npm** (or yarn/pnpm)
  - **MongoDB** (running locally or a connection URI from a provider like MongoDB Atlas)

-----

## 🚀 Getting Started

Follow these steps to get the project up and running on your local machine.

### 1\. Clone the Repository

```bash
git clone https://github.com/alokkcode/SnapURL.git
cd SnapURL
```

### 2\. Setup the Backend

```bash
cd backend
npm install
```

**Configure Environment Variables**

Create a `.env` file in the `/backend` directory and add the following variables.

```env
MONGO_URI=<your mongo-uri>
APP_URL=http://localhost:3000/
JWT_SECRET=<your-jwt-secret>
```

> **Note:** Replace the values with your actual MongoDB URI and a more secure JWT secret for production environments.

### 3\. Setup the Frontend

```bash
cd ../frontend
npm install
```

### 4\. Run the Application

You will need two separate terminal windows to run both the backend and frontend servers concurrently.

**▶️ Start Backend Server (Terminal 1)**

```bash
cd backend
npm run dev
```

**▶️ Start Frontend Server (Terminal 2)**

```bash
cd frontend
npm run dev
```

The application should now be running at `http://localhost:3000` 🎉.

-----


## 📄 License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE) © Alok Kumar.