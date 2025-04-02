To-Do List Application
Overview

This is a To-Do List Application built with HTML, CSS, and JavaScript. It allows users to create, manage, and track tasks with due dates in a visually appealing and interactive interface. The app features a dynamic theme that changes daily, a dark mode toggle, motivational quotes, and persistent storage using the browser's localStorage.

Features

Task Management: Add tasks with optional due dates, mark them as completed, or delete them.
Dynamic Daily Themes: The app's color scheme changes daily based on a predefined set of gradients (e.g., red, purple, blue).
Dark Mode: Toggle between light and dark themes with a button featuring sun/moon icons.
Motivational Quotes: Displays a random motivational quote that updates every 10 seconds.
Persistent Storage: Tasks are saved in the browser's localStorage and persist across page reloads.
Responsive Design: Adapts to various screen sizes with a clean, modern layout.
Animations: Smooth transitions for adding, completing, and deleting tasks, plus hover effects.
Background Effects: Features a fixed background image with a blurred overlay for a sleek look.

File Structure

index.html: The main (and only) file containing the HTML structure, embedded CSS styles, and JavaScript logic.

Technologies Used

HTML5: For the structure of the to-do list app.
CSS3: For styling, animations, and dynamic themes (embedded in <style> tags).
JavaScript: For task management, theme switching, and local storage (embedded in <script> tags).
Unsplash Images: Uses external background images for the body and header.

How It Works

Task Creation:
Enter a task in the text input and optionally select a due date.
Click "Add Task" or press Enter to add it to the list.
Task Interaction:
Check the box to mark a task as completed (strikes through the text).
Click the trash icon to delete a task with a smooth slide-out animation.

Theme Management:

The app sets a daily theme based on the day of the week (0-6).
Toggle between light and dark modes using the top-right button.

Motivation:

A random quote from a predefined list appears in the header and refreshes every 10 seconds.

Persistence:

Tasks are saved to localStorage whenever a task is added, completed, or deleted.
