# Task Manager

A modern, responsive task management application built with React and Vite. This app allows users to create, manage, and track their daily tasks with a clean and intuitive user interface.

## Features

- ✅ **Add Tasks** - Quickly add new tasks with a simple form
- ✏️ **Mark Complete** - Toggle tasks as complete/incomplete
- 🗑️ **Delete Tasks** - Remove tasks from your list
- 📊 **Task Counter** - View count of completed and total tasks
- 🎨 **Responsive Design** - Works seamlessly on desktop and mobile devices
- ⚡ **Fast Performance** - Built with Vite for optimal build speeds

## Tech Stack

- **React 19.2.0** - JavaScript library for building user interfaces
- **Vite 7.3.1** - Next generation frontend build tool
- **Tailwind CSS 4.2.0** - Utility-first CSS framework
- **React Hook Form 7.71.2** - Performant form management
- **ESLint 9.39.1** - Code quality and consistency

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Steps

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd Task-Manager
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint to check code quality

## Project Structure

```
src/
├── components/
│   ├── AddTaskForm.jsx      # Form component for adding tasks
│   ├── TaskItem.jsx         # Individual task item component
│   ├── TaskList.jsx         # Task list container
│   ├── TaskManager.jsx      # Main task manager logic
│   └── TasksCount.jsx       # Task counter display
├── App.jsx                  # Root application component
├── main.jsx                 # Application entry point
├── App.css                  # Application styles
└── index.css                # Global styles
```

## Usage

1. **Add a Task**: Enter a task description in the input field and click "Add Task"
2. **Complete a Task**: Click the checkbox next to a task to mark it as complete
3. **Delete a Task**: Click the delete button to remove a task from your list
4. **View Progress**: Check the task counter to see how many tasks you've completed

## Development

### Code Quality

This project uses ESLint to maintain code quality and consistency. Run the linter with:
```bash
npm run lint
```

### Building for Production

Create an optimized production build:
```bash
npm run build
```

The build output will be in the `dist/` directory.

## Environment Variables

If needed, create a `.env` file in the root directory. The project uses `dotenv` for environment variable management.
