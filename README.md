# Todo App

A simple and stylish To-Do App built with HTML, CSS, and JavaScript. This app allows users to add, check off, and delete tasks. The tasks are saved in the browser's local storage, so they persist even after the page is refreshed.

## Features

- Add tasks to the list.
- Mark tasks as completed by clicking on them.
- Delete tasks using the delete button (represented by a "×").
- Tasks are saved in the browser's local storage, so they remain even after a page reload.
- Responsive design with a visually appealing gradient background.

## Preview

![Todo App Screenshot](../images/ScreenShot.png)

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/AnkitChowdhury30/todo-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd todo-app
    ```

3. Open `index.html` in your web browser to view the app.

## Code Explanation

### HTML Structure

- **Container Div**: Contains the entire app.
- **Todo App Div**: Holds the input field, button, and task list.
- **Input Field**: Used to enter new tasks.
- **Button**: Adds tasks to the list when clicked.
- **Task List (`ul`)**: Displays the list of tasks.

### CSS Styling

- Gradient background and centered todo container.
- Custom styles for the task list and buttons.
- Toggle styles for completed tasks using the `checked` class.
- `user-select: none;` prevents text selection for list items.

### JavaScript Functions

- **`addTask()`**: Adds a new task to the list. If the input is empty, it shows an alert. Each task is appended as an `li` element with a delete button (`span`).
- **`saveData()`**: Saves the current task list to local storage.
- **`showTask()`**: Loads the tasks from local storage and displays them.
- **Event Listener**: Listens for clicks on the task list. Toggles the `checked` class for tasks or deletes tasks when the delete button is clicked.

### Local Storage

Tasks are saved in the browser's local storage, which allows them to persist even after the page is refreshed.

## Project Structure
todo-app/ 
│ ├── images/ 
│ └── todo-img.jpg 
│ └── unchecked.png 
│ └── checked.webp 
│ ├── styles.css
├── main.js
├── index.html
└── README.md
