# PawPlannerApp

feature added by wynnms
Munique Goncalves Tavares
Mateus Abdallah Fonseca
Patricia Matsumura

To set up MySQL database, please follow below steps to import database dump.
- Open MySQL Workbench and connect to your database.
- Go to Server → Data Import.
- Choose Import Options:
- If you have a .sql backup file, select Import from Self-Contained File and browse to your file.
- Select the Target Schema (database to restore into).
- If the database doesn’t exist, create it manually in MySQL Workbench (Create Schema).
- Click Start Import and wait for the process to complete.
- In case, if you are using different login credential to MySQL, please update the login credentials in application.properties file in pawplanner-backend folder (resources).

Go to PawplannerBackendApplication.java and run the application.

To run the frontend side, please open a new tab in the terminal, change the location to the pawplanner-frontend folder and input these commands:
- npm install
- npm install axios
- npm run dev
