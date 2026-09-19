# cafe-reverie-sales-marketing-system

A web-based sales and marketing management system developed for a café to support product management, sales-related operations, customer interaction, and administrative activities.

## 📌 Project Overview

Café Reverie provides a platform where customers can browse available products, interact with the café through reviews and comments, while administrators can manage products, inventory, users, and customer feedback.

The system was developed as a group project for the **CS 2001: 	Internet Technologies** module.

## 🎯 Objectives

* Develop an intuitive and responsive web application
* Support café product and inventory management
* Provide customers with an interface to browse products
* Enable customers to submit reviews and feedback
* Provide administrators with user and content management functionality
* Support customer engagement through marketing-related features

## 🛠️ Technologies Used

* HTML
* CSS
* JavaScript
* PHP
* MySQL
* SQL
* Apache

## ✨ Main Features

### 👤 Customer Features

* User registration and login
* Browse available products
* View product details and prices
* Submit product reviews and ratings
* View previously submitted reviews
* Contact the café through the Help Desk
* FAQ section

### 🔐 Administrator Features

* Admin login and dashboard
* Add and remove product stock
* Manage products
* View customer reviews
* Delete inappropriate reviews
* Respond to customer feedback
* Manage registered users

## 🗄️ Database

The application uses a MySQL database named `cafe`.

The main tables include:

* `new` – User registration, login, and role management
* `comments` – Customer reviews and comments
* `products` – Product details, prices, and stock levels

## 🏗️ System Structure

The application provides separate dashboards based on the user's role.

```text
                    Café Reverie
                         │
             ┌───────────┴───────────┐
             │                       │
           User                    Admin
             │                       │
       ┌─────┴─────┐         ┌───────┴────────┐
       │           │         │        │        │
   Products     Reviews   Products  Reviews  Users
                             │
                          Inventory
```
## 📄 Documentation

The complete project documentation is available in the `documentation` folder.

## 👥 Team

**Group 21**

* Buddhini H.W.I. – Team Leader
* Chandupa W.A.H.
* Dahamika W.D.V.
* Dananjaya W.D.D.
* Dissanayake D.M.T.K.

## 📚 Academic Project

This project was developed as a collaborative academic project focusing on web-based sales and marketing system development.
