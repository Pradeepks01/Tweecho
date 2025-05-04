# Tweecho - Social Media Application
---

## Overview

Tweecho is a social media platform built with the MERN stack (MongoDB, Express, React.js, Node.js) and styled with Tailwind CSS. It allows users to create, comment on, like, and delete posts, as well as follow other users. It also supports features like editing profile information, uploading images with Cloudinary, sending notifications, and more.

## Features

- 🔐 **Authentication** with JSON Web Tokens (JWT)
- 👥 **Follow** users and get suggested users to follow
- ✍️ **Create posts** with text and images
- 🗑️ **Delete posts** (only if you're the owner)
- 💬 **Comment** on posts
- ❤️ **Like** posts
- 📝 **Edit profile info**
- 🖼️ **Edit cover image** and **profile image**
- 📷 **Image uploads** using Cloudinary
- 🔔 **Send notifications**
- 🌐 **Deployment** ready

## Tech Stack

- **Frontend:** React.js, Tailwind CSS, React Query
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Cloud Storage:** Cloudinary for image uploads
- **Notifications:** Real-time notifications for user activities

  ---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/tweecho.git
cd tweecho
```
Backend Setup
Navigate to the backend directory

cd backend
Install dependencies

npm install
### Setup .env file

```js
MONGO_URI=...
PORT=...
JWT_SECRET=...
NODE_ENV=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

Start the backend server
npm run dev
```
```
Frontend Setup
Navigate to the frontend directory

cd frontend
Install dependencies

npm install
Start the frontend development server

npm start
The application will now be running on http://localhost:3000.
```
```


Deployment
You can deploy both the frontend and backend to services like Heroku, Vercel, or Netlify. Make sure to configure your environment variables on your hosting provider.

Cloudinary Configuration
To set up Cloudinary for image uploads, you'll need to create an account on Cloudinary and get the credentials (Cloud Name, API Key, and API Secret) to add to your .env file.
```
```
Future Features
Real-time chat

Direct messaging between users

Post-sharing with friends

Enhanced notifications and email alerts

Dark mode

And more...
```
```
Contributing
Feel free to fork the repository and submit pull requests. If you have any issues or feature requests, please open an issue on the GitHub repo.
