
# Job Sadan – Job Searching Platform 👨‍💻

A full-featured MERN stack application where job seekers can find and apply for jobs, and employers can post and manage job listings.

---



## 📌 Features

### 🧑‍💼 Job Seekers
- Register/login as a job seeker
- Search and filter job listings
- Apply for jobs with one click
- Save jobs to view later
- Update resume and profile

### 🏢 Employers
- Register/login as an employer
- Post, edit, and delete job listings
- View applicants for each job
- Manage company profile

### 🔐 Admin Panel *(optional)*
- View all users
- Approve/reject job postings
- Manage roles and access

---

## 🛠️ Tech Stack

| Tech        | Usage                          |
|-------------|---------------------------------|
| **MongoDB** | Database                       |
| **Express** | Backend framework              |
| **React**   | Frontend UI                    |
| **Node.js** | Runtime environment            |
| **Mongoose**| MongoDB ODM                    |
| **JWT**     | Authentication                 |
| **Bcrypt**  | Password hashing               |
| **TailwindCSS / Bootstrap** | Styling (your choice)  |

---

## 📁 Folder Structure

```

Job-searching-platform/
│
├── backend/             # Express + MongoDB API
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── utils/
│   ├── middleware/
│   ├── .env
│   └── index.js
│
├── frontend/            # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── .gitignore
├── README.md

````

---

## 🔧 Installation & Setup

### 1. Clone the repo

```bash
git clone https://github.com/Somitraa/Job-searching-platform.git
cd Job-searching-platform
````

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=8000
MONGO_URI=your_mongo_connection_uri
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm start
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm start
```

---



## 🙌 Contributing

Contributions are welcome!
Fork the repo, create a new branch, and submit a pull request.

---

## 📄 License

MIT License

---

## 👤 Author

Made with ❤️ by [Somitra Gupta](https://github.com/Somitraa)

```

---

Let me know if you want me to add:
- Badges (build, license, etc.)
- Screenshots or demo GIFs
- API documentation (Swagger/Postman)

I can also tailor it to match your project structure exactly if you share more details.
```
