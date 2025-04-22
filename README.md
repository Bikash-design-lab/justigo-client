# 🚨 Justigo Client

Justigo Client is the **frontend application** of the **Crime Reporting and Tracking System**. It allows citizens to **report incidents**, **track case progress**, and **view crime statistics** through a secure and user-friendly interface.

Built using **React.js**, Justigo provides a modern and responsive user experience tailored for **Citizens**, **Lawyers**, and **Admins**.

---

## 🚀 Features

- ✅ User Registration & Secure Login (JWT)
- 📝 Crime Reporting with media attachments (image/video/document)
- 👁️‍🗨️ Case Status Tracking Dashboard
- 📬 Real-time Alerts & Notifications
- 🔗 Case Sharing (Public & Private Links)
- 📊 Visual Crime Statistics (Charts/Graphs)
- 📜 Judge Verdict & Lawyer Comments
- 👤 Anonymous Reporting Option
- ♿ Responsive & Accessible UI

---

## 🛠️ Tech Stack

| Layer       | Tech Used                    |
|-------------|------------------------------|
| Frontend    | React.js, Vite               |
| Routing     | React Router DOM             |
| State Mgmt  | Context API (Redux optional) |
| API Calls   | Axios                        |
| Charts      | Chart.js / Recharts          |
| Auth Flow   | JWT-based secure login       |
| Hosting     | Netlify / Vercel (optional)  |

---

## 📁 Folder Structure

```
justigo-client/
├── public/
│   └── index.html
├── src/
│   ├── assets/          # Static files (images, icons)
│   ├── components/      # Reusable UI components
│   ├── context/         # Auth and global state context
│   ├── pages/           # Page components (Register, Login, Dashboard, etc.)
│   ├── services/        # Axios setup & API calls
│   ├── App.jsx          # Main app wrapper with routing
│   └── main.jsx         # React DOM entry point
├── .env                 # Environment variables
└── index.css            # Global CSS styles
```

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/justigo-client.git
   cd justigo-client
   ```

2. **Install Dependencies**
   ```bash
   npm install
   # or
   yarn
   ```

3. **Create `.env` File**
   Add your backend API URL:
   ```
   VITE_API_BASE_URL=http://localhost:5000/api
   ```

4. **Run the App**
   ```bash
   npm run dev
   ```

---

## 🔐 Authentication Flow

- JWT-based login
- Token stored in localStorage
- Auth context protects private routes

---

## 🌐 Pages Overview

- `/register` – New user signup
- `/login` – Secure login for all roles
- `/dashboard` – View & track reported cases
- `/report` – Submit new crime reports
- `/case/:id` – Case details and lawyer comments
- `/stats` – Community crime insights

---

## 🤖 Future Enhancements

- Live SMS/Email alert system
- Voice-based reporting support
- PWA support for offline usage
- Language translation/localization
- Victim assistance chatbot

---

## 👨‍💻 Contributing

We welcome contributions! Here's how:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request 🎉

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 📄 Project Presentation

👉 [View Justigo Presentation (PDF)](https://drive.google.com/file/d/1T9Kt4jh1KqJ4F_9M9-JCkD-uz4Aj72V1/view?usp=sharing)


