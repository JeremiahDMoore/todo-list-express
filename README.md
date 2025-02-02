# ToDo List Application

A simple and efficient ToDo list application built using Node.js, Express, and MongoDB. This project serves as a foundational example for creating CRUD (Create, Read, Update, Delete) web applications with a NoSQL database.

## Features

- **Add Tasks**: Easily add new tasks to your to-do list.
- **View Tasks**: Display all your tasks in a clean and organized manner.
- **Edit Tasks**: Update task details as needed.
- **Delete Tasks**: Remove completed or unnecessary tasks.
- **Persistent Storage**: Utilizes MongoDB to ensure your tasks are saved between sessions.

## Technologies Used

- **Node.js**: JavaScript runtime for building the server-side application.
- **Express**: Web framework for Node.js to set up the server and routes.
- **MongoDB**: NoSQL database for storing tasks.
- **EJS**: Embedded JavaScript templating for rendering dynamic HTML pages.
- **CSS**: Styling the application interface.

## Installation

To run this application locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/JeremiahDMoore/todo-list-express.git
   cd todo-list-express
   ```

2. **Install Dependencies**:
   Ensure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed. Then, run:
   ```bash
   npm install
   ```

3. **Configure the Database**:
   Start your MongoDB server. By default, the application connects to a database named `todo-list` on `localhost`. If your configuration differs, adjust the connection settings in `server.js`.

4. **Start the Application**:
   ```bash
   npm start
   ```
   The application will be accessible at `http://localhost:3000`.

## Usage

- **Add a Task**: Enter the task description in the input field and click "Add".
- **Edit a Task**: Click the "Edit" button next to the task, modify the description, and save.
- **Delete a Task**: Click the "Delete" button to remove the task from the list.

## Acknowledgments

This application was developed as a learning project to demonstrate the integration of Node.js, Express, and MongoDB for building CRUD applications.
