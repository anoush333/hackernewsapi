# hackernewsapi
Angular project with Csharp api to get Hacker News API info
HackerStories
HackerStories is a full-stack web application designed to provide a platform for sharing and discovering stories. The project features a robust backend built with .NET Core and a dynamic frontend developed using Angular.

Table of Contents
Features
Technologies Used
Setup Instructions
Running the Application
Running Tests
Project Structure
Contributing
License
Features
User-Friendly Interface: Modern and responsive design.
Story Management: Create, read, update, and delete stories.
Pagination: Efficient display of large datasets.
Caching: Improved performance using server-side caching.
Secure API: Secure and scalable backend with .NET Core.
Technologies Used
Backend:
Framework: .NET Core
Database: MS SQL Server
Testing Framework: xUnit/NUnit/MSTest (depending on the setup)
Caching: Implemented server-side caching.
Frontend:
Framework: Angular
Testing Framework: Jasmine + Karma
Build Tools: Node.js, npm
Setup Instructions
Prerequisites
Backend:
.NET SDK (version 7.0 or later)
MS SQL Server
Frontend:
Node.js (version 16 or later)
Angular CLI (if running locally)
Clone the Repository
bash
Copy code
git clone https://github.com/your-repo/hacker-stories.git
cd hacker-stories
Backend Setup
Navigate to the backend root directory:
bash
Copy code
cd HackerStories
Restore dependencies:
bash
Copy code
dotnet restore
Update the connection string in appsettings.json to point to your SQL Server.
Apply migrations (if applicable):
bash
Copy code
dotnet ef database update
Frontend Setup
Navigate to the frontend directory:
bash
Copy code
cd hacker-stories-frontend
Install dependencies:
bash
Copy code
npm install
Running the Application
Backend
Start the backend server:
bash
Copy code
dotnet run
The API will be available at http://localhost:5000.
Frontend
Start the frontend server:
bash
Copy code
ng serve
Access the application at http://localhost:4200.
Running Tests
Backend
Run all backend tests:

bash
Copy code
dotnet test
Frontend
Run all frontend tests:

bash
Copy code
npm test
