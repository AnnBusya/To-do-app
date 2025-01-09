# React To-Do App

This is a functional To-Do application developed using React. The project demonstrates core React concepts such as component-based architecture, state management, and Context API. It also integrates localStorage for data persistence and provides a smooth user experience with interactive features.

## Technologies Used

- **React**: For building the user interface and managing state.
- **React Context API**: For state management across the application.
- **TypeScript**: Ensuring type safety and better development experience.
- **localStorage**: To persist todos data across browser sessions.
- **SCSS**: For styling and responsive design.

  
## Features

- **Add New ToDo**: Users can add new tasks to their list.
- **Status Management**: Each todo has an ID, title, and a completion status (default: false).
- **Persistent Storage**: Todos are saved in localStorage, ensuring data persists between sessions.
- **Todo Filtering**: Filter tasks by status - All, Active, or Completed.
- **Delete Todos**: Easily remove tasks using the delete button.
- **Clear Completed**: Clear all completed tasks with a single click (button is disabled if no tasks are completed).
- **Toggle Status**: Mark individual tasks as completed or not.
- **Toggle All**: A single checkbox to mark all tasks as completed or uncompleted.
- **Inline Editing**: Double-click on a todo to edit it directly. 
  - Save changes by pressing Enter or clicking outside the input field.
  - Delete the todo if the title is empty.
  - Cancel editing with the Escape key.
- **Dynamic Counter**: Displays the count of active (not completed) todos.



## How to Use

1. Add new tasks using the input field.
2. Manage tasks by toggling their status, editing, or deleting them.
3. Filter tasks based on their completion status.
4. Clear all completed tasks with the "Clear Completed" button.
5. The app automatically saves your tasks, so they remain available even after closing the browser.

## Live Demo

[Try the To-Do App](https://annbusya.github.io/To-do-app/)
