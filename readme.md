
# 📝 Online Exam System – Web API (.NET MVC 4.7.2)

An **Online Exam System Web API** built using **ASP.NET MVC 4.7.2**.
This project provides RESTful APIs to manage online examinations, including user management, question handling, exam creation, and result evaluation.

---

## 🚀 Features

* 👤 User Registration & Authentication
* 🛠 Admin Panel APIs
* 📚 Subject & Question Management
* 📝 Exam Creation & Scheduling
* ⏱ Timed Online Exams
* 📊 Automatic Evaluation & Result Calculation
* 📈 Performance Tracking

---

## 🛠 Tech Stack

* **Framework:** ASP.NET MVC 4.7.2
* **Language:** C#
* **Architecture:** RESTful Web API
* **Database:** SQL Server
* **ORM:** Entity Framework
* **Authentication:** Token / Session Based (customizable)
* **IDE:** Visual Studio

---

## 📂 Project Structure

```
OnlineExamSystem/
│
├── Controllers/        # API Controllers
├── Models/             # Entity Models
├── ViewModels/         # DTOs / Data Transfer Objects
├── Services/           # Business Logic Layer
├── Data/               # Database Context
├── Migrations/         # Entity Framework Migrations
└── Web.config          # Configuration File
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/online-exam-system.git
```

### 2️⃣ Open in Visual Studio

* Open the `.sln` file in **Visual Studio**
* Restore NuGet packages

### 3️⃣ Configure Database

* Update the connection string in `Web.config`:

```xml
<connectionStrings>
  <add name="DefaultConnection" 
       connectionString="Your_SQL_Server_Connection_String" 
       providerName="System.Data.SqlClient" />
</connectionStrings>
```

* Run Entity Framework migrations:

```powershell
Update-Database
```

### 4️⃣ Run the Project

* Press `F5` or click **Start**
* API will run on:

```
https://localhost:xxxxx/
```

---

## 🔑 API Modules

### 👨‍🎓 Student APIs

* Register
* Login
* View Available Exams
* Start Exam
* Submit Answers
* View Results

### 👨‍💼 Admin APIs

* Create Subjects
* Add Questions
* Create Exams
* Assign Questions to Exams
* View Student Results

---

## 🧪 Sample API Endpoints

| Method | Endpoint                 | Description         |
| ------ | ------------------------ | ------------------- |
| POST   | `/api/auth/register`     | Register new user   |
| POST   | `/api/auth/login`        | Login user          |
| GET    | `/api/exams`             | Get available exams |
| POST   | `/api/exams/{id}/submit` | Submit exam answers |
| GET    | `/api/results/{userId}`  | Get user results    |

---

## 🔒 Security

* Role-based Authorization
* Input Validation
* Exception Handling Middleware
* Secure Password Hashing

---

## 📊 Future Enhancements

* JWT Authentication
* Swagger API Documentation
* Email Notifications
* Dashboard Analytics
* Frontend Integration (React / Angular)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **Your Name**
📧 [your-email@example.com](mailto:waseeftauqueera@gmail.com)
🌐 GitHub: [https://github.com/your-username](https://github.com/waseeftauqueer)
