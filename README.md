# Job Portal


This project is a collaboration between Robel Gulima and Yonatan Nigusu for their portfolio project. 
Robel using Django framework to build the backend web application, SQLite 3 to store client data, HTML, CSS,JavaScript and React.js for the frontend; 
and Yonatan deploying the web application in containers,  Puppet manifests to configure the containers.

## Description 
The main purpose of this Job Portal is to provide convenience for Job Seekers in searching for various jobs depending on his qualifications and apply for the job.
The features of this Online Job Portal are user-friendly that users can easily work on it and contains User Types such as Admin, Employer and Job Seeker.

## These are the following features of the Online Job Portal


### **Admin Modules**
This module provides administrator related functionalities. The administrator manages the entire application and maintains the profiles of applicants and employers.
### **Dashboard**Dashboard: In this section, admin can briefly view the total job category, total employer, total candidates, and total job.

### **Employer Module**
This module provides functionalities related to employers. Employers can post vacancy details and update the details as and when necessary. Employers can search through applicant resumes based on different criteria.
Jobs: In this section, an employer can post the job and manage the jobs.
Candidates List: In this section, the employer can view the list of applied candidates and send messages to selected candidates.
Reports: In this section employers can view how many candidates apply for a job in particular periods.
Employers can also update his profile, change the password, and recover the password.

### **Candidates(Jobseeker) Modules**
[**Home**]: In this section, candidates can view job which is posted by an employer and apply for those jobs.
[#Applied Jobs #]: In this section, candidates can view the response of applied jobs.
About Us: In this section, candidates can view the about us page of the website.
Contact Us: In this section, candidates can view the contact us page of the website.
Candidates(Jobseeker) can also update his profile, change the password, and recover the password.

# Front End
* React components handling routing
* Material UI for consistent styling
* API calls to manipulate database

# Back End
* GET, POST, PUT, Delete requests handled
* CRUD manipulation 

# Relational Database
* Handled with ORM 
* Model system with base model handling identification
* Many to many relationship for users and rewards

# Server / Deployment
* Nginx 
* Ubuntu machine

## Technology stack
* HTML
* CSS
* JavaScript
* Python – Django
* SQLite 3
* Node.js
* React.js

## Getting Started

The product is built using a two-tier pattern where the React frontend is decoupled logically and physically from the API backend. To use the product, a short action list must be completed successfully:
-	Compile and start the Django API Backend
      -	by default the server starts on port 8000
-	Compile and start the React UI
      -	UI will start on port 3000 and expects a running backend on port 8000
-	Configuration (Optional)
      -	Change the API port
      -	Configure the API port used by the React UI to communicate with the backend


## Authors
**Robel**: [GitHub](https://github.com/robel625)

**Yonatan Nigusu**

## Challenges
- learning new frameworks/technologies: Django, HTML, CSS, JavaScript, React.js
- serving static files in production 
