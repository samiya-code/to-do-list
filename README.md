# To-Do App

A simple, lightweight to-do list application built with vanilla JavaScript that helps you manage your daily tasks efficiently.

## Features

- **Add Tasks**: Easily add new tasks to your to-do list
- **Mark Complete**: Click on tasks to mark them as completed
- **Delete Tasks**: Remove tasks with the delete button (×)
- **Persistent Storage**: Tasks are saved to localStorage and persist between sessions
- **Clean Interface**: Simple and intuitive user interface

## How to Use

1. **Add a Task**: Type your task in the input box and press Enter or click the add button
2. **Complete a Task**: Click on any task to mark it as completed (strikethrough effect)
3. **Delete a Task**: Click the × button next to any task to remove it from the list

## File Structure

```
to-do/
|-- index.js          # Main JavaScript functionality
|-- index.html        # HTML structure (create this file)
|-- style.css         # CSS styling (create this file)
|-- README.md         # This file
```

## Setup Instructions

1. Create an `index.html` file with the following structure:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="todo-app">
            <h2>To-Do List</h2>
            <div class="row">
                <input type="text" id="input-box" placeholder="Add your task">
                <button onclick="addtask()">Add</button>
            </div>
            <ul id="list-container"></ul>
        </div>
    </div>
    <script src="index.js"></script>
</body>
</html>
```

2. Create a `style.css` file for styling (optional but recommended)

3. Open `index.html` in your web browser

## Technical Details

- **Language**: Vanilla JavaScript
- **Storage**: Browser localStorage
- **No Dependencies**: Works without any external libraries
- **Browser Compatibility**: Works in all modern browsers

## Functionality

The app includes the following core functions:
- `addtask()`: Adds new tasks to the list
- `savedata()`: Saves tasks to localStorage
- `showtask()`: Loads saved tasks on page load
- Event listeners for marking complete and deleting tasks

## Future Enhancements

Potential improvements for future versions:
- Task categories
- Due dates and reminders
- Task priority levels
- Search and filter functionality
- Export/import tasks
- Dark mode toggle

## License

This project is open source and available under the MIT License.
