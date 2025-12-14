# React ToDo App 📋

A simple, functional To-Do List application built using **React**. This project serves as an excellent foundational example for learning core React concepts, specifically focusing on state management and handling user interactions to implement basic data persistence logic (CRUD operations).

## ✨ Key Features

- **Add Tasks:** Input new to-do items and append them to the list.
- **Edit Tasks:** Modify existing task text directly within the list.
- **Delete Tasks:** Remove tasks permanently from the list.
- **Local State Management:** Utilizes the React `useState` Hook to manage the list of tasks and the current task being edited.
- **Clean UI:** Simple, unstyled interface (as per the tutorial code) focused on functionality.

## 🛠️ Technology Stack

- **Framework:** React (Functional Components)
- **Bundler:** **Vite** (for development and build)
- **State Management:** React `useState` Hook
- **Language:** JavaScript (ES6+)
- **Styling:** CSS

## 💻 Getting Started (To Run Locally)

Follow these steps to get a local copy up and running on your machine.

### Prerequisites

- Node.js and npm (or yarn) installed on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/msnonari/react-todo-app.git
    cd react-todo-app
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
3.  **Start the development server:**
    ```bash
    npm start
    # or
    yarn start
    ```

The application will open automatically in your browser at `http://localhost:3000`.

## ⏭️ Next Steps and Potential Enhancements

To take this project further, consider implementing the following features:

1.  **Persistence:** Integrate `localStorage` to save tasks so they persist even after the browser is closed or refreshed.
2.  **"Mark as Complete":** Add a button or checkbox to toggle the task status and apply a strikethrough style.
3.  **Refactoring:** Separate the main `ToDoApp` component into smaller, reusable components (e.g., `ToDoForm`, `TaskItem`).
