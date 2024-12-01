# HackerStories

HackerStories is a full-stack web application for sharing and discovering engaging stories. It features a robust backend built with .NET Core and a dynamic frontend developed using Angular.

---

## 🚀 Features

- **User-Friendly Interface**: Modern, responsive design for seamless user interaction.
- **Story Management**: Create, view, update, and delete stories effortlessly.
- **Pagination**: Optimized performance for large datasets.
- **Caching**: Server-side caching for faster load times.
- **Secure API**: Scalable and secure backend architecture.

---

## 🛠️ Technologies Used

### Backend:
- **Framework**: .NET Core
- **Database**: MS SQL Server
- **Testing Framework**: xUnit/NUnit/MSTest
- **Caching**: Server-side caching for improved performance

### Frontend:
- **Framework**: Angular
- **Testing Framework**: Jasmine + Karma
- **Build Tools**: Node.js, npm

---

## 📂 Project Structure

```plaintext
HackerStories/
├── BackEndServices/        # Backend services and business logic
├── Controllers/            # API controllers for routing
├── Models/                 # Data models
├── hacker-stories-frontend/ # Angular frontend code
│   ├── src/                # Frontend source files
│   ├── package.json        # Frontend dependencies
│   └── tsconfig.json       # TypeScript configuration
├── appsettings.json        # Backend app configuration
├── Program.cs              # Entry point for the backend
└── HackerStories.sln       # Solution file

Setup Instructions
Prerequisites
Backend:
.NET SDK (7.0 or later)
MS SQL Server
Frontend:
Node.js (16 or later)
Angular CLI
Steps
1. Clone the Repository
Run the following commands in your terminal:

bash
Copy code
git clone https://github.com/your-username/hacker-stories.git
cd hacker-stories
2. Backend Setup
Navigate to the backend directory:
bash
Copy code
cd HackerStories
Restore dependencies:
bash
Copy code
dotnet restore
Update the connection string in appsettings.json to point to your SQL Server database.
Apply migrations (if applicable):
bash
Copy code
dotnet ef database update
3. Frontend Setup
Navigate to the frontend directory:
bash
Copy code
cd hacker-stories-frontend
Install dependencies:
bash
Copy code
npm install
▶️ Running the Application
Backend:
Start the backend server:
bash
Copy code
dotnet run
The API will be available at http://localhost:5000.
Frontend:
Start the frontend server:
bash
Copy code
ng serve
Access the application at http://localhost:4200.
🧪 Running Tests
Backend Tests
Run backend tests with:

bash
Copy code
dotnet test
Frontend Tests
Run frontend tests with:

bash
Copy code
npm test
