# Task Tracker

Task Tracker is a **React-based task management application** that allows users to create, manage, and track tasks with due dates and completion statuses. This app demonstrates the use of React state management, local storage persistence, and simple UI components.

## Features

- **Add New Tasks**: Create tasks with titles and due dates.
- **Toggle Task Completion**: Mark tasks as completed or incomplete.
- **Delete Tasks with Confirmation**: Delete tasks after a confirmation prompt to prevent accidental deletions.
- **Local Storage**: Tasks persist between sessions by saving to local storage.
- **Responsive Design**: Clean and simple layout suitable for desktop and mobile.

## Demo

1. Add, Toggle Task Completion and Local Storage

![demo01-tasktracker](https://github.com/user-attachments/assets/f2807e27-1c1b-4f05-8a36-73ccad18aa15)

2. Confirmation before deleting task and Local Storage

![demo02-tasktracker](https://github.com/user-attachments/assets/b4cd1d31-2704-48ca-9616-593bd0df57a8)

3.  Deleted Task  and Local Storage

![demo03-tasktracker](https://github.com/user-attachments/assets/94bf9302-443c-4273-b7da-7ce161c4f6bc)

## Installation and Setup

### Prerequisites

- **Node.js** (v14 or later)
- **npm** or **yarn**

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SamsonNg00/task-tracker.git
   cd task-tracker
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

3. **Run the App**:
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```

   The app will open in your browser at `http://localhost:3000`.

## Usage

- **Add a New Task**: Enter a title and optional due date, then click **Add Task**.
- **Mark Task as Completed**: Toggle the checkbox to mark tasks as completed.
- **Delete a Task**: Click the delete button; a confirmation dialog will appear before deletion.

## Sample Data for Testing

You can use the following JSON data to test in Local Storage under the key `tasks`:

```json
[
  {
    "id": 1730264318955,
    "title": "Complete Project Proposal",
    "dueDate": "2024-10-30",
    "completed": false
  },
  {
    "id": 1730264318956,
    "title": "Team Meeting - Weekly Sync",
    "dueDate": "2024-10-27",
    "completed": true
  }
]
```

## Folder Structure

```
/src
 ├── /components
 │   ├── TaskList.js      # Renders the list of tasks
 │   ├── TaskForm.js      # Form for adding tasks
 │   └── TaskItem.js      # Displays individual tasks with edit and delete options
 ├── App.js               # Main application component
 └── index.js             # Entry point for React
```

## Technologies Used

- **React**: Frontend library for building the UI.
- **Local Storage**: Browser API for data persistence.
- **Vite**: Fast development build tool.

## Contributing

Contributions are welcome! If you’d like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License.

## Contact
For any questions, feedback, or suggestions, feel free to reach out:

- **GitHub**: SamsonNg00
- **Email**: samsonnguyen00@gmail.com
