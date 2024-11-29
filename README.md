***Design documents must include required details of the full version of the system but implementation can be limited to single theater development***

Required design documents:
1. System Introduction
2. Use Case
    - Use case diagram
    - Scenario List
    - 4 sequence/ system interaction diagrams
3. Domain Layer Class Diagram
4. State Transition Diagrams
5. Presentation Layer Class Diagram
6. Package Diagram
7. Deployment Diagram

# Backend Setup Instructions
- using git, clone "backend" repository at https://github.com/AcmePlexApp/backend
- Install MySQL server
- Using sqlWorkbench or other means, Create a localhost MYSQL database schema called "ACME", with user "root" and no password
- Confirm mysql server is running
- In eclipse, install "Spring Boot 4" plugin.
- In eclipse, "open project from folder contents" and navigate to this folder "ACME".  Will open up  the project in Eclipse.
- RUN project as a Java application.  Should start up a server on localhost:8080.
- To confirm back end server is running Open http://localhost:8080/auth/create in a browser - If it is running you should get a 403 Authorization Error in your browser.

# Front End Setup Instructions
- clone "frontEnd" repository using https://github.com/AcmePlexApp/acmeplex
- install node.js
- open a terminal inside the "acmeplex" folder and run the command "npm install".  Confirm that all required packages are installed.
- run the command "npm run dev".  This should show the front end server opening at http://localhost:5173/
- open the server address in a browser window.  You should now be able to interact with the application.
