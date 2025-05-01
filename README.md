# Fullstack Chat App

A full-stack real-time chat application built with **React**, **Express**, **MongoDB**, and **Socket.io**.

## 🚀 Features

- Real-time messaging with Socket.io
- User authentication using JWT
- Cloudinary for image uploads
- Responsive UI with TailwindCSS + DaisyUI

## 🛠️ Tech Stack

**Frontend:** React, Vite, Zustand, TailwindCSS  
**Backend:** Express.js, MongoDB, Socket.io, JWT, Cloudinary

---

## Backend Setup

1. Navigate to the `backend` directory:
    ```bash
    cd backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in `/backend` with the following variables:
    ```
    MONGODB_URI=
    PORT=5001
    JWT_SECRET=
    NODE_ENV=
    CLOUDINARY_CLOUD_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=
    ```

4. Start the backend server:
    ```bash
    npm run dev
    ```

---

## Frontend Setup

1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the frontend:
    ```bash
    npm run dev
    ```

