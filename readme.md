# 🏠 StayNest

> A full-stack web application inspired by Airbnb, built with Node.js, Express, MongoDB, and EJS.

## 📌 About

StayNest is a property listing platform where users can browse, create, edit, and delete property listings.

The project is being built incrementally, with features such as authentication, reviews, and authorization planned for later stages.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express
- **Database:** MongoDB, Mongoose
- **Templating:** EJS, EJS-Mate
- **Frontend:** HTML, CSS, Bootstrap
- **Other:** Method-Override

## ✨ Current Features

- Create property listings
- View all listings
- View individual listing details
- Edit listings
- Delete listings
- MongoDB database integration
- Responsive Bootstrap-based UI
- Reusable EJS layouts and partials
- Responsive navigation and footer

## 📁 Project Structure

```text
StayNest/
├── models/
│   └── listing.js
├── public/
│   └── css/
│       └── style.css
├── views/
│   ├── includes/
│   │   ├── navbar.ejs
│   │   └── footer.ejs
│   ├── layouts/
│   │   └── boilerplate.ejs
│   └── listings/
│       ├── index.ejs
│       ├── show.ejs
│       ├── new.ejs
│       └── edit.ejs
├── server.js
├── package.json
├── package-lock.json
└── README.md
```

## 🔗 Routes

| Method | Route                  | Description              |
| ------ | ---------------------- | ------------------------ |
| GET    | `/listings`            | View all listings        |
| GET    | `/listings/:id`        | View a specific listing  |
| GET    | `/listings/new`        | Show create listing form |
| POST   | `/listings/create`     | Create a listing         |
| GET    | `/listings/edit/:id`   | Show edit listing form   |
| PUT    | `/listings/update/:id` | Update a listing         |
| DELETE | `/listings/delete/:id` | Delete a listing         |

## 🖥️ UI

The current interface includes:

- Responsive navbar
- Listing card grid
- Listing detail page
- Create and edit forms
- Responsive layout
- Shared footer
- Bootstrap components with custom CSS styling

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd StayNest
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start MongoDB

Make sure MongoDB is running locally.

The application currently connects to:

```text
mongodb://127.0.0.1:27017/StayNest
```

### 4. Start the server

```bash
node server.js
```

The application runs on:

```text
http://localhost:3300
```

## 🗺️ Roadmap

- [x] Listing CRUD
- [x] MongoDB integration
- [x] Basic frontend
- [x] Responsive listing UI
- [ ] Error handling
- [ ] Validation
- [ ] Authentication
- [ ] Authorization
- [ ] Reviews and ratings
- [ ] User-specific listings
- [ ] Booking functionality
- [ ] UI refinement

## 📌 Milestones

### Phase 1 — Core Listing Application

- Listing CRUD
- MongoDB/Mongoose integration
- Frontend layout and styling
- Responsive listing interface

### Upcoming

- Validation and error handling
- Authentication and authorization
- Reviews
- Booking functionality

---

Built as a full-stack development project while exploring the Node.js/MERN ecosystem.
