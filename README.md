#Head Hunter
Group project no. 9 of the second edition of the course [MegaK](https://www.megak.pl/). It is a web application built on the basis of full-stack technology.

## Project description
The "Head Hunter" application was created to connect people looking for a job in the IT industry, in particular young programmers called Students, with HR, including Headhunters. The main purpose of the application is to enable students to present their skills in a unified way, and HR to easily find suitable candidates for work, conduct interviews with them and propose cooperation.

Administration of the application rests with the Administrator, who manages access to the Student base. The administrator can specify the method of access to the Student database, which gives him control over the number of "CVs" downloaded by a given user with the type of HR account.

Students start their path in the application by completing their profile, which can be done during the first login. The Student's profile contains various information about his skills and experience.

People from the HR department, after logging into the system, have access to the table containing information about the Students. The table allows you to search and sort by different columns, and HR can add selected Students to the "To talk" list. The number of people HR can add to this list is limited.

After adding the Students to the "For conversation" list, HR has the ability to make decisions about employing a given person. If HR decides to hire someone, information about it is sent to the Administrator.

The application supports three system roles: Admin, Student and HR. Each role has its specific tasks and permissions in the system. The application is available only after registration and logging in, it is not possible to access the system without logging in. User registration is solely managed by the Administrator. The administrator can add new users by importing the list of Students or manually entering the data of a single user from the HR department.

## Technologies
### Frontend
- React
- TypeScript
- React Hook Forms
- Yup
- Tailwind CSS
### Backend
- NestJS
- TypeORM
- MySQL
- Swagger
- Docker

## Links to repositories
- https://github.com/Przekol/megak-v2-head-hunter-gr9-backend
- https://github.com/Muniox/megak-v2-head-hunter-gr9-frontend

## Screen shots

<img width="635" alt="image" src="https://github.com/Annshka/HeadHunter/assets/129051061/cd995f82-1e10-4efc-a0d5-6f9a11c03e9b">
<img width="630" alt="image" src="https://github.com/Annshka/HeadHunter/assets/129051061/f7d6a28b-30b5-4a7b-bb25-eb98507c4a95">
<img width="559" alt="image" src="https://github.com/Annshka/HeadHunter/assets/129051061/20cc115d-fbd0-499d-b274-639adea6e3f5">
<img width="561" alt="image" src="https://github.com/Annshka/HeadHunter/assets/129051061/09009701-bf87-4c81-af9e-1aef9562a67c">

## Authors
The project was created by:

- Agnieszka | **Front-end Developer** | [GitHub](https://github.com/Annshka)
- Joanna | **Front-end Developer** 
- Maciej | **Front-end Developer** 
- Mateusz | **Back-end Developer** 
- Paweł | **Front-end Developer** 
- Przemek | **Scrum Master/Full-stack Developer**


