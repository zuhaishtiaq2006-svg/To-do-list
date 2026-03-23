# To-do-list

A lightweight, responsive task management application designed to help users organize daily tasks efficiently. Features include theme customization, real-time search, and persistent data storage using the browser's local storage API.

## Overview

Pro Task Manager is a frontend-only web application that enables users to create, edit, delete, and track tasks with a clean, intuitive interface. The application supports both light and dark themes and maintains all task data locally without requiring a backend server.

## Features

- Task Management: Add, edit, delete, and mark tasks as complete
- Search Functionality: Filter tasks in real-time by keyword
- Theme Toggle: Switch between light and dark modes with persistent preference
- Local Storage: All tasks are saved automatically and persist across browser sessions
- Responsive Design: Optimized for desktop, tablet, and mobile devices
- Smooth Animations: Subtle transitions for enhanced user experience
- Floating Action Button: Quick access to add new tasks

## Tech Stack

- Frontend: HTML5, CSS3, Vanilla JavaScript
- Storage: LocalStorage API
- Fonts: Google Fonts (Poppins)
- No external dependencies or build tools required

## Project Structure

- index.html: Main application file containing structure, styles, and scripts
- All CSS is embedded within the HTML file for portability
- All JavaScript logic is embedded for single-file deployment

## Installation

1. Clone or download the repository to your local machine
2. Open the index.html file in any modern web browser
3. No server setup or build process is required

## Usage

1. Adding a Task: Click the floating "+" button or use the prompt to enter a new task
2. Completing a Task: Click the checkbox next to any task to mark it as done
3. Editing a Task: Click the task text or "Edit" button to modify its content
4. Deleting a Task: Click the "Delete" button to remove a task permanently
5. Searching Tasks: Type keywords in the search bar to filter the task list
6. Changing Theme: Click the "Dark Mode" or "Light Mode" button in the header to toggle themes

## Data Persistence

All tasks and theme preferences are stored in the browser's localStorage. Data persists across page reloads and browser sessions but is specific to the device and browser used.

## Browser Compatibility

- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

## Customization

To modify the color scheme:

1. Locate the :root CSS variables in the style section
2. Adjust the hex values for --primary, --secondary, --bg-light, --bg-dark, etc.
3. Save and refresh the page to see changes

## License

This project is open source and available for educational and personal use.

## Author

Zuha Ishtiaq
BS Software Engineering Student
COMSATS University Islamabad – Sahiwal Campus

## Contact

- Email: zuhaishtiaq2006@gmail.com
- LinkedIn: linkedin.com/in/zuha-ishtiaq-a86466331
- GitHub: github.com/zuhaishtiaq2006-svg
