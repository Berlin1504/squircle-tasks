Squircle Tasks

A modern, user-friendly task management web application to help you organize daily tasks, track productivity, and visualize your progress with a clean, squircle-inspired design.
Table of Contents

About
Features
Installation
Usage
Screenshots
Technologies
Contributing

About
Squircle Tasks is a lightweight, client-side task manager built to help users stay productive. It allows you to add, complete, and delete tasks, while providing insights into your productivity through a weekly completion chart and AI-generated summaries. Tasks are saved locally in the browser using localStorage, ensuring persistence without a backend. The app features a sleek, modern UI with a squircle aesthetic, smooth animations, and responsive design.
Features

Task Management: Add, complete, and delete tasks with a simple, intuitive interface.
Productivity Tracking: View completion rate, task count, and streak metrics.
Weekly Visualization: A line chart displays tasks completed each day of the week.
AI-Powered Summaries: Get motivational feedback based on your completion rate.
Local Storage: Tasks persist across sessions using browser localStorage.
Responsive Design: Works seamlessly on mobile, tablet, and desktop devices.
Accessibility: Includes ARIA labels for screen reader support.
Smooth Animations: Subtle animations for task input errors and hover effects.

Installation

Clone the repository:git clone https://github.com/berlin1504/squircle-tasks.git


Navigate to the project directory:cd squircle-tasks


Open index.html in a web browser to run the app locally. No server or dependencies are required, as the app uses a CDN for Chart.js.

Alternatively, you can serve the project using a local development server (e.g., with Python):
python -m http.server 8000

Then, visit http://localhost:8000 in your browser.
Usage

Add a Task: Enter a task in the input field and click the "+" button or press Enter.
Complete a Task: Check the box next to a task to mark it as complete.
Delete a Task: Click the trash icon to remove a task.
View Stats: Monitor your completion rate, tasks for the day, and streak in the "Your Week at a Glance" section.
Track Progress: The "Completion Over Time" chart shows tasks completed each day of the week.
Read Summaries: Check the "Daily AI Summary" for productivity insights based on your performance.

Tasks are automatically saved to your browser's localStorage and persist across sessions.

Main interface showing task input, task list, stats, chart, and summary.
Note: Replace screenshots/squircle-tasks.png with an actual screenshot of your app when uploading to GitHub.
Technologies

HTML5: Structure of the web application.
CSS3: Styling with squircle aesthetics, animations, and responsive design.
JavaScript: Core logic for task management and interactivity.
Chart.js: For rendering the weekly task completion chart.
LocalStorage: For persisting tasks in the browser.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

Please ensure your code follows the existing style and includes appropriate comments.
