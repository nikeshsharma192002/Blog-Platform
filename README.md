# Blog Platform Project

A modern, responsive blog platform that allows users to create, read, update, and delete blog posts, with additional features for user authentication, profile management, and rich content interaction. This platform is built using **React.js** on the frontend and optionally **Node.js** and **Express** with **MongoDB** for the backend.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Backend Setup (Optional)](#backend-setup-optional)
- [Frontend Setup](#frontend-setup)
- [Usage](#usage)


## Features

### Core Requirements
- **Blog Post Management**: Create, read, update, and delete blog posts with rich text editor integration and image upload.
- **Categories & Tags**: Organize posts using categories and tags.
- **User Authentication**: Sign up and log in using JWT authentication (if backend is implemented).
- **User Profiles**: Manage profile details including an avatar.
- **Comment System**: Engage with posts by leaving comments.

### Frontend Features
- **Responsive Design**: Mobile-first approach for accessibility across devices.
- **Search Functionality**: Search for posts by keywords.
- **Category Filtering**: Filter posts by categories.
- **Pagination/Infinite Scroll**: View more posts with pagination or infinite scroll.
- **Loading & Error States**: Visual feedback for loading and error handling.

## Tech Stack

### Frontend
- **React.js**: JavaScript library for building user interfaces.
- **Redux**: State management library for consistent global state.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Axios/Fetch**: For making HTTP requests to the backend.

### Backend 
- **Node.js**: JavaScript runtime for server-side programming.
- **Express.js**: Web framework for building REST APIs.
- **MongoDB**: Database for storing blog posts, user data, and comments.
- **JWT**: Authentication for secure user login.

## Getting Started

### Prerequisites
- **Node.js** and **npm** installed on your machine.
- Optionally, a **MongoDB** instance for backend data storage.

### Backend Setup (Optional)
1. Clone the repository and navigate to the backend folder:
   ```bash
   git clone https://github.com/nikeshsharma192002/Blog-Platform.git
   cd Blog-Platform/Blog-Backend

2. Install backend dependencies:
   ```bash
   npm install

3. Set up environment variables. Create a .env file in the backend directory and configure the following:
   ```bash
   PORT=5000
   MONGODB_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret_key>

4. Start the backend server:
   ```bash
   npm start

The server should now be running at http://localhost:5000.

### frontend setup

1. Navigate to the frontend folder:
   ```bash
   cd Blog-Platform/Blog-Frontend

2. Install frontend dependencies:
   ```bash
   npm install

3. Configure API endpoint. In the .env file, specify the backend API base URL:
   ```bash
   REACT_APP_API_BASE_URL=http://localhost:5000

4. Start the frontend server:
   ```bash
   npm start

### Usage

- Register/Login: Create a user account or log in to access the blog dashboard.
- Create Post: Navigate to the dashboard to create a new blog post, add images, and assign categories and tags.
- View Posts: Browse posts, filter by category, and search by keyword.
- Edit/Delete Posts: As an author, edit or delete your own posts.
- Comment on Posts: Leave comments on posts as a logged-in user.

