🍰 Cupcake Store App

A simple, functional mobile application built using Glide (No-Code), created as part of the Projeto Integrador Transdisciplinar II – Engenharia de Software.

The goal of this app is to simulate an online cupcake shop, allowing users to browse products, place orders, and track their own purchases, all using a clean, fast, no-code architecture.

🚀 Features
✔ Cupcake Catalog

Displays all cupcakes with image, name, price, and description

Each cupcake has an individual product detail page

✔ Order Flow

Users can place an order directly from the cupcake detail page

When an order is placed, the app automatically stores:

Cupcake name

Price

Logged user’s email

Date/time of creation

✔ “Orders” Screen

Each user sees only their own orders

Displays:

Cupcake ordered

Price

Status

Date of order

✔ Authentication

Login via email (Glide native authentication)

All order data is tied to the authenticated user

🧩 Data Structure

The app uses Glide Tables as the internal database.
The project contains three tables:

1) Cupcakes
Field	Type	Description
name	Text	Name of the cupcake
description	Text	Short description
price	Number	Cupcake price
image	Image	Product photo
2) Users
Field	Type	Description
name	Text	User's name
email	Email	Login & identification
3) Orders
Field	Type	Description
order_id	Unique ID	Auto-generated order identifier
cupcake	Text	Cupcake ordered
price	Number	Value of the order
user_email	Email	Email of logged-in user
status	Text	"Pending" / "Preparing" / "Delivered"
created_at	Date/Time	Timestamp of the order
🛠 Technology Stack
Layer	Technology
Front-end	Glide App Builder
Back-end	Glide Actions & Tables
Database	Glide Tables
Hosting	Glide Cloud
Coding Mode	No-Code
🌐 Live App

Access the application here:
👉 https://cupcake-store-eu8v.glide.page

🎯 Purpose

This project demonstrates:

Construction of a functional MVP

Use of no-code platforms

Basic database modeling

Requirements engineering

Delivery of a working software prototype

EVIDENCIAS DE TESTE (LAUDO)

<img width="299" height="139" alt="image" src="https://github.com/user-attachments/assets/c3d5f515-06b7-4f8f-af06-9d796b2d90cb" />
Price now has a placeholder of BRL (R$) and Allergy Warning naming is correct. Dark mode is also setted to follow the OS of the user
