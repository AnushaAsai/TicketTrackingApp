# Ticket Tracking App
The application will involve logging, recording and resolving incidents for services in an organization. 

## Built With
  * Technology - MERN Stack
  * Database - MongoDB (https://account.mongodb.com/account/login, username:incidentmanagement2020@gmail.com, password:incident@humber)
  * JSON Web Tokens
  * axios, nodemailer, generate-password, react-router-dom, sessionStorage, Mongoose, react lifecycles 

What things you need to install the software and how to install them

```
Latest Browser
Click on https://incident-management-2020.herokuapp.com/
```
### Roles in the application:
  * Admin
  * Technician
### Steps taken to complete the project: 
  * Created the required models using mongoose
  * Created routes/REST node API for each of the features 
  * Enabled cors 
  * Created react class components for each of the features 
  * Redirection using withRouter
  * Consumed Rest API uisng axios
### Functionality:
  * Admin & Technician login, Admin & Technician dashboard
  * Technicians and admin can create a ticket
  * Only Admin can add new users (technician or admin)
  * Only Admin can close a ticket add notes, change status (edit ticket)
  * Only Admin can reset password
   


