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

## 🖥️ Setup Instructions

### Prerequisites

#### Backend:
- .NET SDK (7.0 or later)
- MS SQL Server

#### Frontend:
- Node.js (16 or later)
- Angular CLI

---

### Steps

#### 1. Clone the Repository
Run the following commands in your terminal:

```bash
git clone https://github.com/your-username/hacker-stories.git
cd hacker-stories

### Backend:
cd HackerStories
Restore dependencies:

Run the following command to restore all required packages:
dotnet restore

 Frontend Setup
Follow these steps to set up the frontend:

Navigate to the frontend directory:

cd hacker-stories-frontend
Install dependencies:

Use the following command to install all required packages:

npm install


Here’s the updated README.md file with proper spacing and formatting for Backend Setup and Frontend Setup, optimized for GitHub:

markdown
Copy code
## 🖥️ Setup Instructions

### Prerequisites

#### Backend:
- .NET SDK (7.0 or later)
- MS SQL Server

#### Frontend:
- Node.js (16 or later)
- Angular CLI

---

### Steps

#### 1. Clone the Repository
Run the following commands in your terminal:

```bash
git clone https://github.com/your-username/hacker-stories.git
cd hacker-stories
2. Backend Setup
Follow these steps to set up the backend:

Navigate to the backend directory:

bash
Copy code
cd HackerStories
Restore dependencies:

Run the following command to restore all required packages:

bash
Copy code
dotnet restore
Update the connection string:

Open the appsettings.json file and update the database connection string to point to your SQL Server instance.

Apply migrations (if applicable):

Use the following command to apply database migrations:

bash
Copy code
dotnet ef database update
3. Frontend Setup
Follow these steps to set up the frontend:

Navigate to the frontend directory:

bash
Copy code
cd hacker-stories-frontend
Install dependencies:

Use the following command to install all required packages:

bash
Copy code
npm install
▶️ Running the Application
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
Backend Tests
Run backend tests with:

dotnet test
Frontend Tests
Run frontend tests with:

npm test
