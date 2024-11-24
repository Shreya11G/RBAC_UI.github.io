# RBAC_UI
Build a Role-Based Access Control (RBAC) User Interface
Role-Based-Access-Control-RBAC-UI
A simple User Management Dashboard built using HTML, CSS, JavaScript, and JSON Server. This dashboard allows administrators to add, edit, and delete user information, such as usernames and emails, through an intuitive and responsive user interface. The project demonstrates how to create a basic CRUD application with a REST API using JSON Server to store and manage data.

Features:
Add Users: Allows users to be added with a username and email. Edit Users: Existing user details can be updated. Delete Users: Users can be removed from the system. Dynamic User Display: Users are dynamically fetched and displayed from the backend (JSON Server). Responsive Design: The UI adjusts to different screen sizes for a seamless experience across devices.

Technologies Used:
Frontend:
HTML: Markup for the structure of the dashboard. CSS: Styling the interface to ensure a clean, user-friendly experience. JavaScript: Handling the logic for CRUD operations, such as adding, editing, and deleting users.

Backend:
JSON Server: A simple fake REST API for data management.

File Structure:
│
├── index.html            # Main HTML file containing the layout
├── style.css             # CSS file to style the dashboard
├── app.js                # JavaScript file for handling user management functionality
├── db.json               # JSON file used by JSON Server to store user data
├── README.md             # Project description (this file)

How It Works:
Adding Users:
Admins can use the form in the dashboard to add new users. Once the form is submitted, the user data is sent to the backend (JSON Server), and the new user is added to the db.json file.

Editing Users:
Users can be edited by clicking the Edit button next to their name. The user’s data will be populated in the form fields, and once the form is submitted, the user’s information is updated in the backend.

Deleting Users:
Users can be deleted by clicking the Delete button next to their name. A confirmation prompt will appear, and upon confirmation, the user is removed from the backend.

Dynamic Display:
The list of users is dynamically fetched and displayed from the backend (JSON Server) each time the page loads or when a user is added, edited, or deleted. Contributing If you want to contribute to the project, feel free to fork the repository and submit pull requests. Suggestions and improvements are always welcome.



Live Demo:
https://abir-0007.github.io/RBAC_UI/
