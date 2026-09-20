# codeAlpha_Project_Management_Tool

TaskFlow - Collaborative Project Management Tool

TaskFlow is a full-stack, real-time project management and collaboration application designed for teams to organize projects, track tasks, and communicate efficiently—similar to Trello or Asana.The application provides a clean and simple interface for managing projects and monitoring task progress efficiently. Users can create projects, add tasks with descriptions, assign tasks to team members, update task statuses, and communicate through task comments.

This project is built as part of an internship project task to demonstrate practical skills in frontend development, backend development, database management, and building interactive web applications.



📸 Application Screenshots

1. Main Workspace & Project Navigation
<img width="1890" height="863" alt="Screenshot 2026-09-20 084541" src="https://github.com/user-attachments/assets/e6b12174-02b0-4941-a778-853e6f416967" />

2. Interactive Task Boards & In-Task Comments
<img width="1894" height="861" alt="Screenshot 2026-09-20 084606" src="https://github.com/user-attachments/assets/35ee35b2-680b-4485-b593-1f0a473ae21a" />

3. Task Creation & Assignment Modal
<img width="1894" height="865" alt="Screenshot 2026-09-20 084626" src="https://github.com/user-attachments/assets/4a5ae171-6638-41b7-a143-8ce405fa2d90" />


✨ Features

- Project Workspaces: Create and manage distinct project boards for team initiatives.
- Task Management: Add tasks with customizable titles, detailed descriptions, assignees, and statuses ('To Do', 'In Progress', 'Completed').
- Task & Project Deletion: Remove outdated projects or task cards using built-in deletion buttons.
- In-Task Discussions: Integrated comment threads on each task card for contextual team communication.
- Multi-User Simulation: Switch active logged-in users to test real-time collaboration workflows.
- Real-Time WebSockets (Socket.io): Instant live updates across all connected clients for project creation, task management, and comments without page refreshes.


🗺️ Project Roadmap
Upcoming features and improvements planned for TaskFlow :

- Drag-and-Drop Kanban Board: Drag task cards seamlessly between status columns ('To Do', 'In Progress', 'Completed').
- Persistent Database: Replace in-memory storage with MongoDB or PostgreSQL.
- JWT Authentication: Secure login/signup system with hashed passwords and protected routes.
- Due Dates & Priority Badges: Add deadline trackers and visual urgency indicators ('High', 'Medium', 'Low').
- File Attachments: Allow users to upload mockups, documents, or screenshots directly inside task comments.
- Dark Mode Toggle: Native dark theme support for improved accessibility and user preference.



📁 Project Structure

project-management-app/
├── node_modules/
├── public/
│   ├── app.js
│   ├── index.html
│   └── style.css
├── .gitignore
├── package.json
├── package-lock.json
└── server.js



