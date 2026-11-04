# Full Stack Employee Management System

A MERN stack application for managing employees: adding, viewing, updating, and removing employee records through a React frontend backed by a Node/Express REST API and MongoDB Atlas.

**Live demo:** https://full-stack-ems-harshh.vercel.app

## Tech Stack

- **Frontend:** React, [Tailwind CSS / CSS: edit as needed]
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (Mongoose)
- **Deployment:** Vercel (client and server deployed as separate projects)

## Features

- [Authentication / login: keep only if you have it]
- Create, read, update, and delete employee records
- [Dashboard / department management: edit to match your app]
- REST API with a separate client and server

## Project Structure

```
FullStackEms/
├── client/   # React frontend
└── server/   # Express API
```

## Getting Started

### Prerequisites

- Node.js 18+
- A MongoDB Atlas connection string

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/hgharsh07-pixel/FullStackEms.git
   cd FullStackEms
   ```

2. Install and run the server:
   ```bash
   cd server
   npm install
   ```
   Create a `.env` file:
   ```
   MONGODB_URI=your_mongodb_atlas_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   ```
   Then start it:
   ```bash
   npm start
   ```

3. Install and run the client:
   ```bash
   cd ../client
   npm install
   ```
   Create a `.env` file:
   ```
   VITE_API_URL=http://localhost:5000
   ```
   Then start it:
   ```bash
   npm run dev
   ```

The client runs on `http://localhost:5173` by default.

## Deployment

The client and server are deployed as two separate Vercel projects. Set the environment variables above in each project's settings, and point the client's API URL to the deployed server.

## Acknowledgements

Built following the Great Stack MERN tutorial, then set up, configured, and deployed independently.

## Author

Harsh Gautam, [GitHub](https://github.com/hgharsh07-pixel)
