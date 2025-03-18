# Zenkai Share - Gaming Clip Sharing App

A simple web application that allows users to upload, share, and view gaming clips. Built for sharing gameplay moments with friends.

## Features

- User account creation and authentication
- Video upload directly from your browser
- Custom titles for your gaming clips
- Download clips shared by other users
- Edit titles of your own uploads
- Modern Steam/Discord-inspired design

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Authentication**: Firebase Authentication
- **Database**: Firebase Firestore
- **Storage**: Cloudinary for video hosting

## Setup Instructions

### 1. Clone this repository

### 2. Setup configuration

This project requires API keys for Firebase and Cloudinary. These are not included in the repository for security reasons.

- Create a `config.js` file in the root directory based on `config.example.js`
- Add your Firebase and Cloudinary credentials to the file

### 3. Firebase Setup

- Create a Firebase project at [firebase.google.com](https://firebase.google.com)
- Enable Email/Password authentication
- Create a Firestore database with collections for "users" and "clips"

### 4. Cloudinary Setup

- Create a Cloudinary account at [cloudinary.com](https://cloudinary.com)
- Create an upload preset with unsigned uploading enabled

## Usage

Simply open the index.html file in your web browser, or deploy to a web hosting service of your choice.

## Note

This project is for personal use between friends. The free tiers of Firebase and Cloudinary should be sufficient for small-scale usage.
