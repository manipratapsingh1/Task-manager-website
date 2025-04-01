# Task-manager-website

This project is a simple, yet effective Task Manager web application designed to help users organize and track their tasks across different categories and priorities. The application allows users to add, view, and manage tasks, generate reports, and visualize task data using interactive charts. The user interface is intuitive, and the application is built with HTML, CSS, and JavaScript to ensure smooth functionality and a responsive design.

Key Features:

Task Addition:

The user can add a new task by filling out a form that requires the following information:

Category: The task can be categorized as "Professional," "Personal," or "Other."

Task Description: A brief description of the task.

Priority: The task priority can be set as "High," "Medium," or "Low."

Status: The status of the task can be marked as "Completed," "Incomplete," or "Pending."

Upon submitting the form, the task is added to the task list and displayed on the screen.

Task List:

A dynamically updated list displays all tasks added by the user, showing the task description, category, priority, status, and the date when the task was added.

The list is organized clearly to allow the user to easily review and manage tasks.

Real-Time Time Display:

A real-time clock updates the current date and time on the page, providing users with an up-to-date view of the time.

Report Generation:

The application allows the user to generate a report that visually displays task data through various types of charts. These include:

Task Status Report: A pie chart that shows the distribution of tasks based on their current status (Completed, Incomplete, Pending).

Task Distribution by Category: A bar chart that shows how tasks are distributed among the different categories (Professional, Personal, Other).

Task Distribution by Priority: A doughnut chart that shows how tasks are distributed based on their priority (High, Medium, Low).

These charts help users quickly understand the status and distribution of their tasks.

User Interaction:

Buttons for Viewing and Generating Reports:

"Show Tasks" button displays the current task list.

"Generate Report" button creates the charts and displays them along with the report text.

Responsive Design:

The application is designed to be responsive and user-friendly on both desktop and mobile devices, ensuring a seamless experience on various screen sizes.

Data Visualization:

Charts are generated using the Chart.js library, making it easy for users to visualize the statistics about their tasks. The charts are dynamically updated based on the tasks added to the list.

Technical Details:

HTML: The structure of the web page is created using HTML. It defines the layout of the task manager, including input fields for task data, task list display, and buttons for interacting with the app.

CSS: Custom styling is applied using CSS to ensure the app has a clean, modern look. The design is responsive, adjusting for different screen sizes, and provides a user-friendly experience.

JavaScript: JavaScript is used to handle the interactivity of the app. The functionality includes:

Adding tasks to the list.

Dynamically updating the task list when a new task is added.

Handling form validation and clearing inputs after a task is added.

Generating reports and visualizing task data using Chart.js.

Chart.js: A JavaScript library that provides easy-to-use methods for creating various types of interactive charts, such as pie charts, bar charts, and doughnut charts. These are used to display task statistics, making it easy for users to assess their task data visually.

Project Structure:

HTML File (index.html):

Contains the structure of the web page, including headers, input forms, buttons, and sections for the task list and charts.

CSS Styles:

Contains custom styles for the web application to make it look attractive and ensure a seamless user experience across different devices.

JavaScript File:

Contains all the logic for interacting with the user interface, adding tasks, updating the task list, and generating reports with the help of Chart.js.

How the Application Works:

The user selects the category, enters a task description, sets the priority, and chooses the task status from dropdown menus.

When the "Add Task" button is clicked, the task is added to an array and displayed on the page. The task list updates in real time, reflecting all the tasks added.

The user can generate a report by clicking the "Generate Report" button, which will display a set of charts that visualize the task data (status, category, and priority).

The time is displayed at the top of the page and updates every second.

Possible Future Enhancements:

Task Editing: Allow users to edit their tasks after they have been added.

Task Deletion: Provide an option to remove tasks from the task list.

Task Due Dates: Add a feature to specify and display due dates for tasks.

User Authentication: Add user authentication and allow users to save their tasks across sessions.

Conclusion: This Task Manager web application is a useful tool for individuals who want to stay organized and keep track of their tasks efficiently. It combines task management with data visualization to provide insights into task distribution and status, making it a powerful tool for personal and professional productivity. The simplicity of the app, along with the real-time features and interactive charts, makes it easy to use and provides a satisfying experience.







