# 📝 TODO App

Welcome to the **TODO App** project! This application is built using **React.js** with **Next.js** as the framework, based on a tutorial by [Spruce Emmanuel](#). It's a simple yet powerful tool to manage your daily tasks.

## 🚀 Features

- ✅ **Add New TODOs**: Easily add tasks to your list.
- ✏️ **Edit & Delete TODOs**: Modify or remove existing tasks with ease.
- ✔️ **Mark TODOs as Completed**: Track your progress by marking tasks as complete.
- 📊 **Track Completed TODOs**: Keep an overview of all completed tasks.

## 📚 Table of Contents

- [Project Setup](#project-setup)
- [Components](#components)
- [Styling](#styling)
- [Functionality](#functionality)
- [Persisting Data](#persisting-data)
- [Conclusion](#conclusion)

## 🛠️ Project Setup

To set up the project locally, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/Kidist21/todo-app.git
    ```

2. **Navigate to your project directory**:

    ```bash
    cd todo-app
    ```

3. **Create a new Next.js app**:

    ```bash
    npx create-next-app@latest
    ```

4. **Start the development server**:

    ```bash
    npm run dev
    # or with yarn
    yarn run dev
    ```

## 🧩 Components

The app is organized into several core components:

- **📌 Header Component**: Displays the app's title.
- **🦸 TODOHero Component**: The main interface for managing tasks.
- **📝 Form Component**: Handles input for adding new TODOs.
- **📋 TODOList Component**: Displays the list of tasks with interactive options.

## 🎨 Styling

Basic yet clean CSS is used to style the application, ensuring a user-friendly experience while keeping the focus on functionality.

## ⚙️ Functionality

### ➕ Adding TODOs
- Users can add tasks via the form component, updating the app's state.

### 🛠️ Editing & Deleting TODOs
- Modify or remove tasks directly from the TODO list.

### ✔️ Marking TODOs as Completed
- Users can mark tasks as complete, helping them track progress.

## 💾 Persisting Data

To maintain TODOs across sessions, the app uses `localStorage`:

- **Saving Data to localStorage**: Automatically saves the current state.
- **Loading Data from localStorage**: Retrieves the TODOs upon app startup.

## 🎉 Conclusion

This TODO App is a great starting point for learning React.js and state management. Whether you're new to React or looking to brush up on your skills, this project is a valuable exercise in building functional and interactive user interfaces.



