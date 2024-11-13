# 📝 Todo App

A simple and interactive Todo App built to help you manage your daily tasks efficiently. This application allows you to add, edit, mark as completed, and delete tasks in an intuitive way. Perfect for keeping track of your to-dos and staying organized!

## 🚀 Features

- **Add Tasks**: Quickly add new tasks to the list with a description.
- **Edit Tasks**: Modify tasks and update their content as needed.
- **Mark Complete**: Mark tasks as complete to track your progress.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Persistent Storage**: Your tasks are stored in `localStorage`, so they remain even after refreshing the page.

## 🛠️ Technologies Used

- **React**: A JavaScript library for building user interfaces, ensuring a dynamic and responsive experience.
- **Context API**: Manages the state and provides a centralized store for the todos across the application.
- **Tailwind CSS**: Custom styles to give the app a clean and modern look.
- **localStorage**: Keeps tasks saved between sessions, ensuring your data is never lost.

## 🖼️ Screenshots

_Add screenshots here to showcase your app's design and functionality._

![Screenshot of Todo App](./src/assets/Screenshot%202024-11-13%20182216.png);

## 📂 Project Structure

```plaintext
├── public
│   └── index.html
├── src
│   ├── components
│   │   ├── TodoForm.js      # Component for adding new tasks
│   │   └── TodoItem.js      # Component for individual task items
│   ├── contexts
│   │   └── TodoContext.js   # Context API to manage state
│   ├── App.js               # Main application component
│   └── index.js             # Entry point
└── README.md
```
