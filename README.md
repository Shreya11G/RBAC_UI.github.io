RBAC_UI
Create a Role-Based Access Control (RBAC) User Interface

RBAC User Management Dashboard: This straightforward User Management Dashboard is constructed using HTML, CSS, JavaScript, and JSON Server. It provides administrators with the functionality to add, modify, and remove user details such as usernames and emails through a user-friendly and adaptive interface. The project illustrates how to develop a fundamental CRUD application with a REST API using JSON Server for data storage and management.

Key Features:
Add Users: Easily add new users with their username and email.

Edit Users: Update existing user information seamlessly.

Delete Users: Effortlessly remove users from the system.

Dynamic User Display: Fetch and display users dynamically from the backend (JSON Server).

Responsive Design: The user interface adapts to different screen sizes, ensuring a smooth experience across various devices.

Technologies Utilized:
Frontend:

HTML: The markup language for structuring the dashboard.

CSS: Responsible for styling the interface, ensuring it is clean and user-friendly.

JavaScript: Manages the logic for CRUD operations such as adding, editing, and deleting users.

Backend:

JSON Server: Provides a simple fake REST API for data management.

File Structure:
│
├── index.html        # Main HTML file containing the layout
├── style.css         # CSS file to style the dashboard
├── app.js            # JavaScript file for handling user management functionality
├── db.json           # JSON file used by JSON Server to store user data
├── README.md         # Project description (this file)
Functionality:
Adding Users: Administrators can use the form on the dashboard to add new users. Once submitted, the data is sent to the backend (JSON Server), adding the new user to the db.json file.

Editing Users: Users can be edited by clicking the "Edit" button next to their name. Their data will populate the form fields, and once submitted, the user's information is updated in the backend.

Deleting Users: Users can be removed by clicking the "Delete" button next to their name. After a confirmation prompt, the user is removed from the backend.

Dynamic Display: The user list is dynamically fetched and displayed from the backend (JSON Server) each time the page loads or when a user is added, edited, or deleted.

Live Demo:
Check out the live demo at https://shreya11g.github.io/RBAC_UI.github.io/
