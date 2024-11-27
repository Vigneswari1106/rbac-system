# Role-Based Access Control (RBAC) System

## Description

This project is a Role-Based Access Control (RBAC) System built with **Node.js**, **Express**, and **MongoDB**. It allows the management of users, roles, and permissions dynamically, enabling secure and structured access control for different user types, such as Admins, Moderators, and Clients.

Authentication is currently based on **Email & Password**, though the system is flexible and can easily integrate other authentication mechanisms via OAuth/OAuth2.0 (such as Google, Facebook, Apple, GitHub, etc.).

The application is built following the **MVC (Model-View-Controller)** architecture, which separates concerns and ensures scalability.

**Mongoose** is employed as the Object Data Modeling (ODM) tool to interact with the MongoDB database, ensuring efficient storage and retrieval of user information.

For user authentication, the system uses **Passport.js**, providing secure local login using email and password.

---

## Features

- **User Management**: Easily manage and assign roles to users.
- **Role-Based Access Control**: Enforce access based on roles (Admin, Moderator, Client).
- **Authentication**: Supports email and password authentication.
- **Easy to Extend**: Easily integrate OAuth authentication options like Google, Facebook, etc.
- **Database**: Stores user and role data in MongoDB.

---

## To start setting up the project

Step 1: Clone the repository

```bash
git clone https://github.com/Vigneswari1106/rbac-system.git
cd rbac-system
```

Step 2: Install dependencies:

```bash
npm install
```

Step 3: Create a .env file in the root directory with the following keys:

```bash
PORT=3000
MONGO_URI=mongodb://localhost:27017/your_db_name
SECRET_KEY=your_secret_key

```
Step 4: Start the server:

```bash
npm start
```

Step 5: Open your browser and navigate to:

```bash
http://localhost:3000
```

# Screenshots
### Dashboard
![alt text](image.png)

<br>

### Manage Users
![alt text](image-1.png)

### Profile
![alt text](image-2.png)

<br>

# License

This project is free to use and does not contain any licensing restrictions.

## Contact

If you have any questions or would like to get in touch, feel free to reach out:

**Developer**: Vigneswari S.  
Email: [vigneswari2024@gmail.com](mailto:vigneswari2024@gmail.com)  
LinkedIn: [https://linkedin.com/in/vigneswari-s-090046330/](https://linkedin.com/in/vigneswari-s-090046330/)

---

