## ![Capture](https://github.com/user-attachments/assets/01785b86-b0d2-4358-8413-3aac074fa4a1)
# Online-ToDo-App
MongoDB based  ToDo App to keep Track of  all the things that need to be done



- This is a simple To-Do app built with Node.js, Express, and MongoDB. It allows users to add, view, and delete tasks. The app uses MongoDB as the database to store the to-do items and integrates with Mongoose for object modeling.

## Features

1. Add new to-do items
2. View all to-do items
3. Delete to-do items

## Technologies Used

- **Node.js**: JavaScript runtime to build the server.
- **Express.js**: Web framework for building the backend.
- **MongoDB**: NoSQL database to store to-do items.
- **Mongoose**: ODM for interacting with MongoDB.
- **Body-Parser**: Middleware to parse incoming request bodies.
- **Nodemon**: Tool for automatic server restarting during development.

## Setup

### Prerequisites

1. **Node.js**: Make sure you have Node.js installed on your machine.
   You can download it from [Node.js](https://nodejs.org/).

3. **MongoDB**: You need a MongoDB account (or a local instance) to store your data. 
   You can sign up for a free MongoDB Atlas cluster here: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

# How To Run 
1. Download This File
2. Extract it
3. Then Install Node.js
4. Then Install MongoDB
5. Open Terminal in Folder
6. Run : npm nodemon app
7. OpenBrowser : 127.0.0.1:3000/todo (Visit The localHost/todo)


API Endpoints
1. GET /todo
Fetches all to-do items from the database and renders them.

2. POST /todo
Adds a new to-do item to the database. You can send the data in the request body (e.g., { item: "Buy groceries" }).

3. DELETE /todo/:item
Deletes a to-do item from the database based on the item’s name. The name is passed as a parameter in the URL (e.g., /todo/Buy%20groceries).

Contributing
Feel free to fork this project and submit pull requests. If you find any bugs or have suggestions for improvements, please open an issue in the GitHub repository.

License
This project is licensed under the MIT License - see the LICENSE file for details.


## Author
- HAMYL Aththanayaka
- 2nd Year Bsc.It UnderGraduate
- Faculty Of Applied Science Universty Of Vauniya



  ## Samples

Front End :

  

  ![image](https://github.com/user-attachments/assets/4021794d-6fa6-4948-b21d-9423a8d5d802)


Back End :

![image](https://github.com/user-attachments/assets/705198ba-cc9f-439c-b68a-cd725a93e6a8)


