# 📞 Contact Manager - Full Stack App

A full-stack Contact Manager built with **ReactJS**, **.NET Core Web API**, and **PostgreSQL**.

---

## ✨ Features

- ✅ View all contacts
- ✅ Add new contacts
- ✅ Edit existing contacts
- ✅ Delete contacts
- ✅ Responsive frontend using normal CSS
- ✅ Backend built with .NET Core Web API
- ✅ Database connected via PostgreSQL + EF Core

---

## 🛠️ Tech Stack

**Frontend:**  
- ReactJS  
- Axios  
- Normal CSS  
- Vite (for fast builds)

**Backend:**  
- ASP.NET Core Web API  
- Entity Framework Core  
- PostgreSQL  
- Swagger (for testing APIs)

---

## ⚙️ Project Structure

ContactManagerApp/ ├── ContactManagerAPI/ # .NET Core API backend │ ├── Controllers/ │ ├── Models/ │ ├── Services/ │ ├── Repositories/ │ ├── Data/ (ApplicationDbContext) │ └── appsettings.json ├── contact-manager-frontend/ # ReactJS frontend │ ├── Components/ │ ├── Services/ (Axios setup) │ ├── App.jsx │ └── index.css

## 🚀 How to Run Locally

### 🔹 Backend

```bash
cd ContactManagerAPI
dotnet restore
dotnet ef database update
dotnet run

➡️ Runs on: https://localhost:5034
🔹 Frontend

cd contact-manager-frontend
npm install
npm run dev

➡️ Runs on: http://localhost:5173

