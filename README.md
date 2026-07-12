# Blog Management System

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![EJS](https://img.shields.io/badge/EJS-Template-B4CA65?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3)

A simple **Blog Management System** built with **Node.js, Express.js, MongoDB, and EJS**. The application allows users to browse blog posts while administrators can manage blog content through a dedicated dashboard.

</div>

---

## Overview

This project is a full-stack blog application following the MVC architecture. It provides a clean interface for readers and an admin panel for managing blog posts.

---

## Features

### User

- View all blog posts
- Read post details
- Search posts by keyword
- Responsive interface
- About page
- Contact page

### Admin

- Admin dashboard
- Create blog posts
- Edit blog posts
- Delete blog posts
- Manage blog content

---

## Tech Stack

| Technology | Description |
|------------|-------------|
| Node.js | Backend runtime |
| Express.js | Web framework |
| MongoDB | NoSQL database |
| Mongoose | MongoDB ODM |
| EJS | Template engine |
| JavaScript | Client-side scripting |
| CSS3 | Styling |

---

## Project Structure

```text
Blog
├── public
│   ├── css
│   ├── img
│   └── js
├── server
│   ├── config
│   ├── helpers
│   ├── models
│   └── routes
├── views
│   ├── admin
│   ├── layouts
│   ├── partials
│   └── *.ejs
├── app.js
├── package.json
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone <repository-url>
```

### Navigate to the project

```bash
cd Blog
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Create a `.env` file.

```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string
```

### Run the application

```bash
npm start
```

or

```bash
npm run dev
```

---

## Application Routes

| Route | Description |
|--------|-------------|
| `/` | Home page |
| `/post/:id` | View blog post |
| `/search` | Search blog posts |
| `/about` | About page |
| `/contact` | Contact page |
| `/admin` | Admin dashboard |
| `/admin/add-post` | Create a new post |
| `/admin/edit-post/:id` | Edit a post |

---

## Database Models

### User

- Username
- Password
- Created At

### Post

- Title
- Body
- Created At
- Updated At

---

## Screenshots

Add screenshots of the application here.

Example:

```text
screenshots/
├── home.png
├── post.png
├── search.png
├── admin-dashboard.png
├── add-post.png
```

---

## Future Improvements

- User authentication
- User registration
- Rich text editor
- Categories and tags
- Comment system
- Image upload
- Pagination
- Dark mode
- SEO optimization

---

## Learning Objectives

This project was developed to practice:

- Express.js routing
- MVC architecture
- MongoDB integration
- CRUD operations
- EJS templating
- Search functionality
- Server-side rendering

---

## Author

**Phí Trọng Khôi**

GitHub: https://github.com/phitrongkhoi2k4-lang

---

## License

This project was developed for educational purposes.
