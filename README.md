# 📝 Flask CRUD API Project

## 🚀 Introduction

This project is a basic CRUD (Create, Read, Update, Delete) application built with Flask. 
It demonstrates how to use Flask and SQLAlchemy to perform CRUD operations with a simple to-do list.

## 🌟 Features

- ➕ Create new tasks
- 📖 Retrieve and display tasks
- ✏️ Update existing tasks
- 🗑️ Delete tasks

## 🛠️ Project Structure

- **app.py**: Main application file containing routes and logic.
- **templates/**: Directory containing HTML templates (`index.html` and `update.html`).

## 📚 API Endpoints

- **GET** `/`: Retrieve and display all tasks
- **POST** `/`: Add a new task
- **GET** `/delete/<int:id>`: Delete a task by ID
- **GET & POST** `/update/<int:id>`: Update a task by ID

## 🔧 How It Works

1. **Main Page**: Displays all tasks and allows adding new ones.
2. **Delete Task**: Click the delete button next to a task to remove it.
3. **Update Task**: Click the update button next to a task to modify its content.

---
Happy coding! 🎉
Aryan019
