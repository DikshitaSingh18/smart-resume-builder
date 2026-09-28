Smart Resume Builder

A full-stack web application for creating and customizing professional resumes.

Overview

Smart Resume Builder provides a web-based interface that allows users to build, edit, and preview resumes in an organized and user-friendly environment.

Features

- Create and edit resume information
- Organize different resume sections
- Preview resume content
- User-friendly resume builder interface
- Separate frontend and backend architecture
- Responsive web interface

Project Structure

smart-resume-builder/
│
├── client/
│   ├── public/
│   └── src/
│
├── server/
│   ├── configs/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   └── routes/
│
├── .gitignore
└── README.md

Technologies Used

Frontend

- React
- JavaScript
- Vite
- HTML
- CSS

Backend

- Node.js
- Express.js
- JavaScript

Getting Started

Prerequisites

Make sure you have Node.js and npm installed on your computer.

Clone the Repository

git clone https://github.com/DikshitaSingh18/smart-resume-builder.git
cd smart-resume-builder

Run the Frontend

Open a terminal and run:

cd client
npm install
npm run dev

Run the Backend

Open another terminal and run:

cd server
npm install
npm start

The frontend and backend should then run in their respective development environments.

Environment Variables

If the application requires environment variables, create a ".env" file in the appropriate directory and add the required configuration.

Do not commit ".env" files, passwords, API keys, or other sensitive information to the repository.

Project Status

The project is currently available as a full-stack resume-building application and can be extended with additional templates, customization options, and resume-management features.

License

This project is for educational and development purposes.
