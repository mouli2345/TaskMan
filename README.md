# TaskMan - Your Friendly Task Manager

A modern React task management application built with Vite that helps you organize, track, and complete your tasks efficiently.

## Features

- ✅ **Task Management** - Create, update, and delete tasks
- 📅 **Calendar View** - Interactive calendar to visualize tasks by date
- ⏰ **Real-time Clock** - Live clock display with current date
- 🎯 **Priority & Categories** - Set task priorities (High, Medium, Low) and categories (General, Work, Personal)
- 📊 **Progress Tracker** - Monitor task completion progress
- 📝 **Due Dates** - Assign due dates to tasks
- 💾 **Local Storage** - Tasks persist across browser sessions

## Tech Stack

- **React** - UI library
- **Vite** - Build tool and dev server
- **CSS** - Modern styling with responsive design

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/mouli2345/TaskMan.git

# Navigate to project directory
cd TaskMan

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

## Project Structure

```
src/
├── Components/
│   ├── Calendar.jsx      - Calendar component
│   ├── Clock.jsx         - Real-time clock display
│   ├── Progresstracker.jsx - Progress bar component
│   ├── Taskform.jsx      - Task input form
│   └── Tasklist.jsx      - Task list display
├── App.jsx               - Main application component
├── Style.css             - Global styles
└── main.jsx              - Entry point
```

## Usage

1. **Add a Task** - Enter task name, set priority, category, and optional due date
2. **View Calendar** - See all your tasks on the calendar
3. **Mark Complete** - Click "Complete" to mark a task as done
4. **Delete Task** - Remove tasks you no longer need
5. **Track Progress** - Watch your completion percentage increase

## Features Coming Soon

- Task filtering and sorting
- Recurring tasks
- Task reminders
- Dark mode
- Export/Import functionality

## License

This project is open source and available under the MIT License.
