# Task Management Application.

Welcome to the Task Management Application! This application allows users to manage tasks efficiently with a sleek UI and seamless user experience. Users can create, edit, update, delete tasks, and even drag task cards for interactivity, thanks to the Framer Motion library. Additionally, users can view detailed information about each task on a separate details page. User authentication ensures that only logged-in users can access the application features.

## Run Locally

Clone the project

```bash
 https://github.com/ruchipriya1009/Task_Management_App
```

Go to the project Client directory

```bash
  cd Task_Management/client
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

Go to the project server directory

```bash
  cd Task_Management/server
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Tech Stack

**Frontend:** HTML, CSS, Tailwind CSS, JSX, React.js <br/>
_libraries:_ Redux, axios, React-router-dom, react-icons, Framer Motion, React Toastify <br/>
**Backend:** Node.js, Mongodb, Express.js <br/>
_libraries:_ Argon2, CORS, JSON Web Token<br/>

# Project Type

- Full Stack (Frontend and Backend)

# Deployed Link

https://warm-bombolone-a335a5.netlify.app/

# Features

- **User Authentication**: Secure signup and login with JWT tokens. Only authenticated users can interact with the application.
- **Private Routes**: Access to the task management dashboard is restricted to logged-in users.
- **Task Management**: Create new tasks, Edit existing tasks, Update task status or content, Delete tasks.
- **Task Dragging**: Task cards can be dragged and reorganized using Framer Motion for enhanced user interactivity.
- **Task Details Page**: Users can click on a task to view detailed information about it.

# Landing Page

- A brief overview of the app with an intuitive task management interface, powered by React and Redux.

![image](https://github.com/user-attachments/assets/e5622753-e1c4-4b23-88fd-1003602b9151)


# Authentication

- **SignUp and SignIn**: Secure user registration and login with password hashing (argon2) and JSON Web Tokens (JWT).

![image](https://github.com/user-attachments/assets/543f4ed9-af3e-4009-b645-44397e241c29)
![image](https://github.com/user-attachments/assets/874c0cc6-a922-4134-a489-c31e10db49fb)



## Task Management

# Task Creation

- **Task Creation**: Add new tasks to your to-do list.

![alt text](./client/src/assets/taskadd.png)

- **Task Edit & Update**: Modify the details of your existing tasks.

![image](https://github.com/user-attachments/assets/d52ca56d-4cc3-4891-bab9-abefd364f74e)


-- **Task Deletion**: Remove completed or irrelevant tasks with ease.

![alt text](./client/src/assets/modification.png)

# Task Dragging (Framer Motion)

- **Drag & Drop**: Interact with task cards by dragging and dropping them into new positions.

# Task Details Page

- **View Full Task Details**: Click on any task to view more information such as description, due date, and priority.

# FAQ

- **Is the website optimized for mobile devices?**
- Yes, the application is fully responsive and provides a seamless experience across devices.

- **How is user authentication handled?**
- Authentication is managed using JSON Web Tokens (JWT), ensuring secure access to private routes. Passwords are securely hashed using argon2.

# Project Directory Structure

```plaintext
TASK-MANAGEMENT/
├── client/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   │   ├── landingpage.png
│   │   │   ├── loginpage.png
│   │   │   ├── modification.png
│   │   │   ├── react.png
│   │   │   ├── taskadd.png
│   │   │   ├── taskupdate.png
│   │   ├── components/
│   │   │   ├── detailspage.jsx
│   │   │   ├── home.jsx
│   │   │   ├── login.jsx
│   │   │   ├── navbar.jsx
│   │   │   ├── signup.jsx
│   │   │   ├── task.jsx
│   │   │   ├── updateTask.jsx
│   │   ├── private/
│   │   │   └── privateroute.jsx
│   │   ├── redux/
│   │   │   ├── actions.jsx
│   │   │   ├── reducer.jsx
│   │   │   └── store.jsx
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   └── vite.config.js
├── server/
│   ├── config/
│   │   └── db.js
│   ├── controller/
│   │   ├── alltask.controller.js
│   │   ├── deletetask.controller.js
│   │   ├── edittask.controller.js
│   │   ├── login.controller.js
│   │   ├── newtask.controller.js
│   │   └── register.controller.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── model/
│   │   ├── task.model.js
│   │   └── user.model.js
│   ├── routes/
│   │   ├── logintask.route.js
│   │   └── task.route.js
│   ├── .env
│   ├── index.js
│   └── package.json
├── .gitignore
├── README.md
├── package-lock.json
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vercel.json
└── vite.config.js
```
