# Role Based Access Control 

# Description 

This project is a Role-Based Access Control (RBAC) System built with Node.js, Express, and MongoDB. It allows the management of users, roles, and permissions dynamically, enabling secure and structured access control for different user types, such as Admins, Moderators, and Regular Users.

For authentication we have only Email & Password option but other authentication options using OAuth/OAuth2.0 like Google, Facebook, Apple, GitHub, etc, can be easily incorporated.

The application is based on the **MVC pattern** i.e. Model View Controller.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.



---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/role-based-access-control
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```

Step 4: Install MongoDB (Linux Ubuntu)

See <https://docs.mongodb.com/manual/installation/> for more infos

Step 5: Run Mongo daemon

```bash
sudo service mongod start
```

Step 6: Start the app by

```bash
npm start
```

## Author

- [**Truly Mittal**](https://trulymittal.com)

## Contribute

You can fork this repo and send me a PR.

## License

This project is licensed under the MIT License.
