# 🌐 Basic React Routing Application

## 📌 Overview

This project demonstrates client-side routing in React using React Router.
It includes multiple routes, navigation using NavLink, API data fetching,
and a 404 Not Found page while maintaining SPA behavior.

---

## 🎯 Objectives

* Implement client-side routing using React Router
* Create multiple pages without page reload
* Fetch and display API data
* Handle invalid routes using a 404 page

---

## 🧩 Routes Implemented

| Route    | Description             |
| -------- | ----------------------- |
| /home    | Home Page               |
| /aboutus | About Us Page           |
| /todos   | Displays first 10 todos |
| *        | 404 Not Found           |

---

## 🗂 Folder Structure

```
src/
 ├── components/
 │    ├── Navbar.jsx
 │    ├── Home.jsx
 │    ├── AboutUs.jsx
 │    ├── Todos.jsx
 │    └── NotFound.jsx
 ├── App.js
 ├── index.js
 └── App.css
```

---

## 🧠 Features

* SPA navigation using BrowserRouter
* Navbar visible across all pages
* Todos fetched from JSONPlaceholder API
* Grid-based todo cards
* Clean and readable UI
* 404 page for invalid routes

---

## 🛠 Technologies Used

* React
* React Router DOM
* JavaScript
* CSS
* Fetch API

---

## 🚫 Rules Followed

* No anchor (`<a>`) tags used
* No page reloads during navigation
* Proper use of BrowserRouter, Routes, Route, NavLink
* Clean component separation

---

## 🎓 Learning Outcomes

* Understanding client-side routing
* SPA navigation concepts
* API data handling
* Route-based component rendering

---

⭐ If you find this project useful, feel free to star the repository!
