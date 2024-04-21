# Student-Faculty Interaction Platform

## Overview

The Student-Faculty Interaction Platform is a web-based application designed to facilitate communication and collaboration between students and faculty members. The platform provides features such as faculty profiles, meeting scheduling, timetable access, and project collaboration tools to enhance interactions within the university community. The goal of the project is to offer a centralized hub to streamline student-faculty interactions and engagement.

## Tech Stack
### Development Stack
- **Frontend:** Angular with JavaScript/TypeScript/CSS/HTML.
- **Backend:** Node.js with MySQL for data storage.

### Dependencies
- Node.js
- Angular CLI
- MySQL

## Setup Instructions
1. **Clone Repository:** 
   - Clone the frontend repository: `git clone https://github.com/<your-username>/frontend.git`
   - Clone the backend repository: `git clone https://github.com/<your-username>/backend.git`

2. **Navigate to Directories:**
- Frontend: `cd frontend`
- Backend: `cd backend`

3. **Install Dependencies:**
- Frontend:
  - `npm install`
  - `npm install -g @angular/cli`
- Backend: 
  - `npm install`

4. **Configure Frontend Routing:**
- Update routing configuration in `src/app/app-routing.module.ts`
- Define routes for each component
- Import and add components to routing module
- Ensure routes match backend API endpoints

5. **Configure Backend Server:**
- Install MySQL locally if not already installed
- Create a database and user for the project 
- Update MySQL credentials in `src/config/db.config.js`
- Define models and create tables if needed
- Ensure API endpoints match frontend routes

6. **Run the Project:**
- Backend:
  
  npm start

  

- Frontend:
  
  ng serve --open
  


## Usage

1. Clone the repository: `git clone https://github.com/your-username/project-name.git`
2. Install dependencies: `npm install`
3. Start the development server: `npm start`
4. Open your browser and navigate to `http://localhost:3000`
5. Explore the features such as faculty guide, meeting scheduling, timetable access, academic opportunities, and project collaboration.
6. Students and faculty members can register and log in to access personalized features.
7. Ensure to follow the platform guidelines for smooth usage.

## Contributors
- [Abhishek Soni](https://github.com/ABHISHEKSONI121)
- [Tarun Jain](https://github.com/Noodulf)
- [Shreya Gupta](https://github.com/shhreyaya)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to acknowledge Sonia Khetarpaul, Professor at Shiv Nadar University, for her guidance on this DBMS project.



