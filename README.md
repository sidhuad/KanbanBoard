
# KanBan App

![Static Badge](https://img.shields.io/badge/License-MIT-green)

## Description

- **Motivation**: The motivation behind building this Kanban app is to provide a simple, efficient way for teams and individuals to manage tasks and track progress in a visual, easy-to-use environment. This app helps streamline workflow management, providing a digital board where users can create, update, and track the status of tasks (tickets).By integrating a PostgreSQL database with Supabase for user authentication and data storage, this project serves as a full-stack solution for task management. This app can be particularly useful for teams who need a simple tool to organize their tasks, as well as those looking to learn about full-stack development, CRUD operations, and authentication using JWT tokens.
- **Why build This Project**: This Kanban app was built to:Solve the challenge of managing and visualizing tasks in an easy and intuitive way.Learn and practice full-stack development with modern technologies, including PostgreSQL, Supabase, JWT authentication, and CRUD functionality.Build a project that could be extended in the future with additional features like notifications, task prioritization, and real-time collaboration.
- **What problem's did it solve**: This app addresses several pain points:Task Management: Provides an easy-to-use digital Kanban board for organizing tasks.Authentication: Allows secure user authentication via JWT tokens to ensure only authorized users can create and update tasks.Real-time Updates: As tasks are updated, users can see changes in real-time, providing an efficient workflow.Data Persistence: With PostgreSQL integration via Supabase, the data is securely stored and can be accessed or updated at any time.
- **Lesson's Learned**: Database Integration: Setting up a PostgreSQL database on Supabase and integrating it with the application allowed for secure and efficient data storage and management.JWT Authentication: Implementing JWT for authentication taught me about token-based authentication systems, which are crucial for building secure, scalable applications.Full-Stack Development: Gained experience building both the backend and frontend of an application and learned how to connect them seamlessly.CRUD Operations: Working with creating, reading, updating, and deleting tickets taught me how to effectively manage resources in an application.
- **What makes your project stand-out**: Full-Stack Implementation: Combines both frontend and backend technologies for a seamless experience, making it a solid example of a modern web application.User Authentication: The integration of JWT tokens adds a layer of security, ensuring each user’s data remains private and protected.CRUD Functionality: Allows users to create, read, update, and delete tickets, providing full flexibility in task management.PostgreSQL with Supabase: A cloud-based database solution that’s scalable and easy to set up, which simplifies the backend for both developers and users.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Future Add-ons](#future-add-ons)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)
- [Questions](#questions)
- [Links](#links)

## Installation
- Prerequisites:Node.js (v16 or higher),PostgreSQL database (on Supabase or locally),A GitHub account (if you want to contribute or fork the project)
- Clone the Repository:
```
git clone git@github.com:sidhuad/KanbanBoard.git
cd KanbanBoard
```
- Install Dependencies
```
npm install
```
- Set up a PostgreSQL database on Supabase or locally.
- Create a .env file in the root directory of your project and add the necessary environment variables:
```
DB_URL=your_supabase_database_url
DB_Password=your_password
DB_NAME=db_name
DB_USERNAME=db_username
JWT_SECRET=your_jwt_secret
```
- Start the development Server
```
npm run dev
```

## Usage
1. Sign Up and Log In:

    - To start using the Kanban app, sign up for a new account or log in if you already have one.
    - After signing up, a JWT token will be assigned to authenticate your session.

2. Create New Tickets:

    - Navigate to the "Create Ticket" section.
    - Add a title, description, and set an initial status for the ticket (e.g., "To Do").

3. Update Ticket Status:

    - Drag and drop tickets between columns (e.g., "To Do", "In Progress", "Done").
    - The status of the ticket will be automatically updated in the database.

4. Manage Your Tickets:

    - You can edit or delete tickets as needed by clicking on them.

## Credits
React, node.js, PostgreSQL, Supabase, JWT, Express, Bootstrap, Render

## License
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code. https://choosealicense.com/licenses/mit/

## Future Add-ons
- Task Prioritization: Adding priority levels to tickets (low, medium, high) to improve task management.
- Real-Time Collaboration: Implementing WebSockets or polling to allow multiple users to collaborate and update tasks in real-time.
- Notifications: Adding notifications when a ticket's status changes or when deadlines are approaching.
- Task Filtering: Filtering tasks based on status, priority, or due date.

## How to Contribute

1. Fork the Repository
- check installation guide for cloning, fork the repo

2. Create a New Branch
```
git checkout -b feature/your-branch-name
```

3. Make Your Changes and Add them
```
git add -A
```

4. Commit Your Changes
```
git commit -m "changes"
```

5. Push to your fork
```
git push origin main feature/your-branch-name
```

6. Open a pull Request

## Tests
```
npm run test
```

## Questions
- For Further Questions and Bug reports Please reach out to me at Github [sidhuad](https://github.com/sidhuad) or email me at adarshsidhu83@gmail.com

## Links
- Use Username: JollyGuru (uppercase J and G) and password: password for login.
- [Deployed site](https://kanbanboard-r49j.onrender.com/)
- [Github Repo](https://github.com/sidhuad/KanbanBoard)