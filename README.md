========================================================================
                      PROJECT SETUP INSTRUCTIONS
========================================================================

Prerequisites Required:
- Java JDK 17 or higher
- Node.js (v18 or higher)
- MySQL Database / Server

------------------------------------------------------------------------
STEP 1: DATABASE SETUP
------------------------------------------------------------------------
1. Open your MySQL client (MySQL Workbench, phpMyAdmin, or CLI).
2. Create a new database or import the provided SQL file:
   - File Name: database.sql (included in this folder)
3. Ensure the database connection settings match your local setup in 
   the Spring Boot configuration.

------------------------------------------------------------------------
STEP 2: BACKEND RUN INSTRUCTIONS (Spring Boot)
------------------------------------------------------------------------
Option A (Running the JAR file directly):
1. Open Command Prompt / Terminal in this folder.
2. Run the following command:
   java -jar backend-app.jar

Option B (If running from Source Code):
1. Navigate to the /backend directory.
2. Run: 
   ./mvnw spring-boot:run   (Linux/Mac)
   mvnw.cmd spring-boot:run (Windows)

* The backend server will start on: http://localhost:8080

------------------------------------------------------------------------
STEP 3: FRONTEND RUN INSTRUCTIONS (React / Vite)
------------------------------------------------------------------------
Option A (Serving Production Build):
1. You can serve the static files inside the /build (or /dist) folder 
   using any web server (e.g., Live Server, Nginx, or `npx serve -s dist`).

Option B (If running from Source Code):
1. Navigate to the /frontend directory.
2. Install dependencies:
   npm install
3. Start the development server:
   npm run dev  (or npm start)

* The frontend application will be available at: http://localhost:5173 
  (or http://localhost:3000)

========================================================================
               THANK YOU FOR EVALUATING OUR PROJECT!
========================================================================
