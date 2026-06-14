# StreamHub Backend API

A production-ready video sharing platform backend inspired by YouTube, built using Node.js, Express.js, MongoDB, and Cloudinary. The application provides secure authentication, video management, subscriptions, playlists, likes, comments, watch history, and channel analytics through RESTful APIs.

## Features

### Authentication & Authorization

* User Registration & Login
* JWT Access Token Authentication
* Refresh Token Mechanism
* Secure Logout
* Password Change Functionality
* Protected Routes Middleware
* Cookie-Based Authentication Support

### User Management

* User Profile Management
* Update Account Information
* Upload and Update Avatar
* Upload and Update Cover Image
* View Current User Details
* Channel Profile APIs
* Watch History Tracking

### Video Management

* Upload Videos
* Upload Thumbnails
* Cloudinary Media Storage Integration
* Update Video Details
* Delete Videos
* Publish / Unpublish Videos
* Fetch Single Video
* Fetch All Videos
* User Video Management

### Playlist System

* Create Playlists
* Update Playlists
* Delete Playlists
* Add Videos to Playlist
* Remove Videos from Playlist
* Retrieve User Playlists

### Comments System

* Add Comments on Videos
* Update Comments
* Delete Comments
* Fetch Video Comments

### Like System

* Like / Unlike Videos
* Like / Unlike Comments
* Like / Unlike Tweets
* Retrieve Liked Videos

### Subscription System

* Subscribe to Channels
* Unsubscribe from Channels
* View Channel Subscribers
* View Subscribed Channels

### Tweet Feature

* Create Tweets
* Update Tweets
* Delete Tweets
* Retrieve User Tweets

### Dashboard Analytics

* Channel Statistics
* Channel Video Analytics
* Creator Dashboard APIs

### Security Features

* JWT Authentication
* Password Hashing using Bcrypt
* Protected Route Middleware
* Secure Cookie Handling
* Environment Variable Configuration

---

## Tech Stack

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose ODM

### Authentication

* JWT (JSON Web Tokens)
* Bcrypt

### File Storage

* Cloudinary
* Multer

### Additional Tools

* Cookie Parser
* CORS
* Nodemon
* Prettier

---

## Project Structure

```bash
src/
├── controllers/
├── models/
├── routes/
├── middlewares/
├── db/
├── utils/
├── app.js
└── index.js
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/streamhub-backend.git
cd streamhub-backend
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
PORT=8000

MONGODB_URI=

ACCESS_TOKEN_SECRET=
ACCESS_TOKEN_EXPIRY=

REFRESH_TOKEN_SECRET=
REFRESH_TOKEN_EXPIRY=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

### Run Development Server

```bash
npm run dev
```

---

## API Modules

| Module        | Features                           |
| ------------- | ---------------------------------- |
| Users         | Authentication, Profile Management |
| Videos        | Upload, Update, Delete, Publish    |
| Comments      | CRUD Operations                    |
| Likes         | Video, Comment & Tweet Likes       |
| Playlists     | Playlist Management                |
| Subscriptions | Channel Subscriptions              |
| Tweets        | Social Feed Features               |
| Dashboard     | Analytics & Statistics             |

---

## Highlights

* RESTful API Architecture
* Scalable Folder Structure
* Cloud-Based Media Storage
* JWT Authentication & Authorization
* MongoDB Aggregation Pipelines
* Modular Controller Design
* Production-Ready Backend Practices

---

## Future Enhancements

* Real-Time Notifications
* Live Streaming Support
* Video Recommendations
* Search & Filtering
* Admin Dashboard
* AI-Based Content Suggestions

---

## Author

Developed by Madan B B

Built with Node.js, Express.js, MongoDB, Cloudinary, and JWT Authentication.
