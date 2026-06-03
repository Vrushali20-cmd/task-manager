📋 Task Manager (File-Based)
A simple, lightweight Task Manager application built with Node.js, Express, and EJS. This project uses the built-in File System (fs) module for storage, where each task is saved as an individual .txt file instead of using a traditional database.

🚀 Features
Create Tasks: Easily create new tasks that are automatically stored as text files.

View Tasks: Display all saved tasks directly on the homepage.

Read Details: Click on any task to view its full content.

Edit Tasks: Rename your existing task files.

🛠 Tech Stack
Backend: Node.js, Express.js

Frontend: EJS (Embedded JavaScript Templating), Tailwind CSS

Storage: Local File System (fs module)

📦 Setup Instructions
Clone the repository:

Bash
git clone <your-repo-link>
cd task-manager
Install dependencies:

Bash
npm install
Start the server:

Bash
node index.js
Access the application:
Open http://localhost:3000 in your browser.

📁 Project Structure
Plaintext
├── files/          # Directory where all task .txt files are stored
├── views/          # EJS templates (index, show, edit)
├── public/         # Static assets (CSS/JS)
├── index.js        # Main application logic
└── .gitignore      # Configuration to ignore node_modules
