# BloggingSphere

## Description
BloggingSphere is a full-stack blogging application built using the MERN stack (MongoDB, Express.js, React, Node.js). This application allows users to create, read, update, and delete blog posts. It also includes user authentication and authorization, enabling users to register and log in to manage their own posts.

## Images
- **Login Form**
  <img width="1431" alt="LoginPage" src="https://github.com/user-attachments/assets/fb02ed0d-693e-4c09-b2b6-03b3329b6307" />

- **Register Form**
  <img width="1437" alt="RegisterPage" src="https://github.com/user-attachments/assets/b4835b2e-cc85-4512-bb1d-69ed2600ddb6" />

- **Home Page**
<img width="1426" alt="HomePage" src="https://github.com/user-attachments/assets/0ba1ecef-8105-4621-b27a-d3749a43497a" />

- **Dashboard Page**
  <img width="1431" alt="Dashboard_CreateBlog" src="https://github.com/user-attachments/assets/bbfef657-6350-42d4-afae-cb3e23ce366e" />

- **Blogs Page**
  <img width="1429" alt="BlogsPage" src="https://github.com/user-attachments/assets/25931613-ae92-4547-a4aa-27a00823242f" />

- **Creators Page**
  <img width="1434" alt="CreatorsPage" src="https://github.com/user-attachments/assets/c2b7e8d9-6898-46e5-ac3c-8903377e59a6" />

## Features
- **User Authentication**: Register, Login, Logout
- **CRUD Operations**: Create, Read, Update, and Delete blog posts
- **User-specific Post Management**: Users can manage their own posts
- **Responsive Design**: Ensures usability across various devices

## Technologies Used

### Frontend
- **React**: A JavaScript library for building user interfaces
- **Redux**: State management library
- **Axios**: Promise-based HTTP client
- **Tailwind CSS**: Styling

### Backend
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine
- **Express.js**: Web framework for Node.js

### Database
- **MongoDB**: NoSQL database
- **Mongoose**: MongoDB object modeling tool

### Authentication
- **JSON Web Tokens (JWT)**: For secure user authentication
- **bcrypt**: For password hashing

## Installation

### Prerequisites
- **Node.js**: Install from [Node.js official website](https://nodejs.org/)
- **MongoDB**: Install from [MongoDB official website](https://www.mongodb.com/)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/BloggingSphere.git
   cd BloggingSphere
   ```

2. Set up environment variables:
   ```env
   PORT=5000
   MONGODB_URI=your-mongodb-uri
   JWT_SECRET=your-secret-key
   ```

3. Run the application:
   - Open two terminal windows:
     **Terminal One:**
     ```sh
     cd backend
     npm start
     ```
     **Terminal Two:**
     ```sh
     cd frontend
     npm run dev
     ```
4. Open localhost:5173 and voila!!
   
## Contributing
We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository to your own GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch with a descriptive name for your feature or bug fix.
4. Make your changes and commit them with clear and descriptive commit messages.
5. Push your changes to your forked repository.
6. Open a Pull Request to the main repository, providing a detailed description of your changes and the problem they solve.

Please make sure your code adheres to our coding standards and passes all tests. Thank you!





