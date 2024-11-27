📜 Description
This project is a Role-Based Access Control (RBAC) System built with Node.js, Express, and MongoDB. It allows the management of users, roles, and permissions dynamically, enabling secure and structured access control for different user types, such as Admins, Moderators, and Regular Users.

🛠️ Features
User Management
Manage user accounts, including creating, editing, and deleting user profiles.
Role Management
Define and assign roles (e.g., Admin, Moderator, User) with specific permissions.
Dynamic Permissions
Grant or restrict Read, Write, and Delete operations based on assigned roles.
Authentication
User authentication with email and password using Passport.js.
📋 Technologies Used
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Authentication: Passport.js
Frontend: HTML, CSS, JavaScript
Tools:
Nodemon for development
bcrypt for password hashing
🚀 Getting Started
Prerequisites
Node.js installed
MongoDB instance running locally or on the cloud
Installation
Clone this repository:

git clone https://github.com/yourusername/rbac-system.git
cd rbac-system
Install dependencies:

npm install
Create a .env file in the root directory with the following keys:

PORT=3000
MONGO_URI=mongodb://localhost:27017/your_db_name
SECRET_KEY=your_secret_key
Start the server:

npm start
Open your browser and navigate to:

http://localhost:3000
📂 Project Structure
rbac-system/
│
├── models/
│   ├── User.js          # User schema
│   ├── Role.js          # Role schema
│   └── Permission.js    # Permission schema
│
├── routes/
│   ├── auth.js          # Authentication routes
│   ├── users.js         # User management routes
│   ├── roles.js         # Role management routes
│
├── views/
│   ├── layouts/         # Layout files
│   ├── partials/        # Partial components
│   └── pages/           # Main UI pages
│
├── public/              # Static assets (CSS, JS, images)
├── app.js               # Main server file
├── .env.example         # Example environment variables
├── README.md            # Project documentation
└── package.json         # Project metadata and dependencies

📷 Screenshots
Dashboard
![alt text](image.png)

Manage User
![alt text](image-1.png)

Profile
![alt text](image-2.png)

📝 License
This project is free to use and does not contain any licensing restrictions.

📧 Contact
Developer: Vigneswari S
LinkedIn: linkedin.com/in/vigneswari-s-090046330/
