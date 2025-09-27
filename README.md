# User CRUD App

A simple User Management CRUD application built with Node.js, Express, MongoDB, and EJS.
This project allows you to Create, Read, Update, and Delete users, with a clean Tailwind + custom CSS styled UI.

## 🚀 Features

- Create a new user with name, email, and image URL

- Display all users in a responsive grid

- Update user details

- Delete a user

- Styled with TailwindCSS + custom glassmorphism theme

- Server-side rendering using EJS templates

## 🛠️ Tech Stack

- Backend: Node.js, Express.js

- Database: MongoDB + Mongoose

- Frontend: EJS (templating engine), Tailwind CSS, custom CSS

- Other: Express middleware (body parser, static files)

## 📂 Project Structure

user-crud-express/
│
├── models/
│   └── user.js         # User schema with Mongoose
│
├── public/
│   └── stylesheets/    # CSS files (custom + Tailwind)
│
├── views/
│   ├── index.ejs       # Create user form
│   ├── read.ejs        # List all users
│   ├── edit.ejs        # Edit user form
│
├── app.js              # Main Express app
├── package.json        
└── README.md



