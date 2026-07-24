========================================================================
                      PROJECT SETUP INSTRUCTIONS
========================================================================

Tech Stack:
- Frontend: React (Node.js)
- Backend: C# (.NET Web API)
- Database: PostgreSQL (Hosted on Neon Console)

Prerequisites Required:
- .NET 8.0 SDK (or required .NET Runtime)
- Node.js (v18 or higher)
- Active Internet Connection (Required to connect to Cloud Database)

------------------------------------------------------------------------
STEP 1: DATABASE
------------------------------------------------------------------------
- The database is fully hosted on Neon Cloud Database.
- No local database installation or restoration is required.
- An active internet connection is needed for the backend to connect to Neon DB.

------------------------------------------------------------------------
STEP 2: BACKEND RUN INSTRUCTIONS (C# .NET)
------------------------------------------------------------------------
Option A (Running the Pre-compiled Executable / Published Build):
1. Open Command Prompt / Terminal in the published backend directory.
2. Run the executable file:
   dotnet YourProjectName.dll
   (OR double click YourProjectName.exe if running on Windows)

Option B (Running from Source Code):
1. Navigate to the backend directory where the .csproj file is located.
2. Run the following command:
   dotnet run

* The backend API server will start on http://localhost:5000 (or https://localhost:7001)

------------------------------------------------------------------------
STEP 3: FRONTEND RUN INSTRUCTIONS (React)
------------------------------------------------------------------------
Option A (Serving Production Build):
1. You can serve the static build files inside the /dist (or /build) folder 
   using a web server or by running:
   npx serve -s dist

Option B (Running from Source Code):
1. Navigate to the /frontend directory.
2. Install dependencies:
   npm install
3. Start the React development server:
   npm run dev  (or npm start)

* The frontend application will be available at: http://localhost:5173 
  

========================================================================
               THANK YOU FOR EVALUATING OUR PROJECT!
========================================================================
