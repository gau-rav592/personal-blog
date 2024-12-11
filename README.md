# Personal Blog Platform

A simple personal blog platform that allows users to view and create blog posts. The platform is deployed on **Netlify** with a backend API.

---

## Features
- Homepage displaying blog posts
- Create a new blog post
- Responsive design
- REST API for handling blog data

---

## Architecture Overview

This project follows a **frontend-backend architecture**:

- **Frontend**: Built using React.js and deployed on **Netlify**.
- **Backend**: Built using Node.js with Express.js and serves a REST API. The backend uses an in-memory data store and is hosted locally for this deployment process.

---

## Setup Instructions

### Prerequisites
Ensure you have the following installed on your machine:
- Node.js (v16 or higher)
- npm (Node Package Manager)
- Git

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://https://github.com/gau-rav592/personal-blog.git
   cd personal-blog/frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

   The frontend will be available at `http://localhost:3000`.

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd personal-blog/backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the backend server:
   ```bash
   npm start
   ```

   The backend will be available at `http://localhost:5000`.

---

## Deployment Process

### Step 1: Deploy Frontend to Netlify

1. Push your project to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. Log in to [Netlify](https://www.netlify.com/) and create a new site.
3. Connect your GitHub repository.
4. Select the `frontend` folder for deployment.
5. Follow the deployment process, and after it's completed, Netlify will provide you with a live URL for the frontend.

### Step 2: Use Local Backend (for simplicity)
Since the backend is not deployed, you need to run it locally using the setup instructions above. Ensure the frontend correctly points to `http://localhost:5000` for API requests.

(Optional: Deploy the backend using services like Heroku, Render, or Railway for a complete deployment setup.)

---

## Live Demo
- **Frontend (Netlify)**: [Your Netlify URL](https://your-netlify-url.netlify.app)
- **Backend**: Run locally on `http://localhost:5000`

---

## Project Directory Structure
```
personal-blog/
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
├── backend/
│   ├── index.js
│   ├── package.json
│   └── ...
├── README.md
└── .gitignore
```

