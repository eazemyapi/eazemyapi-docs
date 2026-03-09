# Using AI to Generate Backend

EazeMyAPI includes an **AI backend generator** that allows you to create a complete backend by simply describing your application.

Instead of manually designing tables and APIs, the AI automatically creates the backend structure for you.

Describe your app → AI creates database → APIs ready instantly.

---

## Step 1 — Open the AI Generator

Login to your EazeMyAPI dashboard.

Create a new project using the **AI generator**.

Guide:

[Creating Your First Project](../docs/create-project.md)

---

## Step 2 — Describe Your Application

Enter a short description of the backend you want to create.

Example prompt:

```
Create a backend for a food delivery app with users, restaurants, menu items and orders.
```

Another example:

```
Build a backend for a social media app with users, posts, comments and likes.
```

---

## Step 3 — AI Generates the Database Structure

EazeMyAPI AI automatically creates:

* Database tables
* Table fields
* Relationships between tables

Example generated tables:

Users
Restaurants
MenuItems
Orders

You can modify or extend these tables anytime.

Guide:

[Creating Tables](../docs/create-tables.md)

---

## Step 4 — APIs Are Generated Automatically

Once the tables are created, REST APIs are instantly generated.

Example endpoints:

```
GET /orders
POST /orders
PUT /orders/{id}
DELETE /orders/{id}
```

Guide:

[Generating APIs](../docs/generate-api.md)

---

## Step 5 — Secure Your APIs

All API requests require the API signature key.

Example header:

```
X-API-SIGNATURE: your-secret-key
```

Guide:

[Authentication](../docs/authentication.md)

---

## Step 6 — Connect Your Frontend

Now you can connect your APIs to any frontend application.

Supported platforms include:

* React
* Next.js
* Flutter
* Android
* iOS

Guide:

[Frontend Integration](../docs/frontend-integration.md)

---

Your backend is now fully functional and ready for development.
