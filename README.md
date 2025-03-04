# PERN Login System

Overview

This project is a full-stack authentication system built using the PERN stack (PostgreSQL, Express.js, React, Node.js). It provides a secure login and registration system along with web scraping functionality.

# Features

User Authentication: Secure login and registration system

Frontend: Built using React, Vite, and Tailwind CSS for a fast and responsive UI

Backend: Node.js and Express.js for handling API requests

Database: PostgreSQL for storing user data

Web Scraping: Automated data extraction using scripts

RESTful API: Designed for seamless communication between frontend and backend

Technologies Used

Frontend: React, Vite, Tailwind CSS

Backend: Node.js, Express.js

Database: PostgreSQL

Other: Web scraping scripts (Node.js)

# Project Structure

pern-login-master
│── client  # Frontend (React, Vite, Tailwind CSS)
│   │── src
│   │── public
│   │── index.html
│   └── package.json
│
│── server  # Backend (Node.js, Express.js, PostgreSQL)
│   │── database.sql
│   │── db.js
│   │── server.js
│   │── routes.rest
│   └── package.json

# Installation & Setup

1. Clone the repository

git clone https://github.com/your-username/pern-login.git
cd pern-login

2. Install dependencies

Frontend

cd client
npm install
npm run dev

Backend

cd server
npm install
node server.js

3. Database Setup

Create a PostgreSQL database

Run database.sql to set up the tables

Update db.js with your database credentials

Usage

Open the frontend at http://localhost:5173

Register a new user or log in with existing credentials

The backend API will handle authentication and database interactions

# Contributing

Feel free to fork this repository and submit pull requests.




