🏥 HealthNexus

Smart Healthcare Appointment & Management System

<p align="center">
  A full-stack healthcare platform connecting patients, doctors, and administrators through a centralized appointment management system.
</p><p align="center">
  <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-Framework-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
</p><p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-features">Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-project-structure">Structure</a>
</p>---

📌 Overview

HealthNexus is a MERN-stack healthcare appointment and management application developed as an internship project. It simulates a digital healthcare environment where patients can book appointments, doctors can manage their schedules, and administrators can oversee operational workflows.

The application combines a public healthcare website with role-based dashboards, authentication, and appointment management features.

«Project branding: Parts of the application may use the updated name CareVista.»

✨ Features

🌐 Public Website

- 🏠 Home page and healthcare information
- 🩺 Doctor directory and departments
- 📅 Appointment booking page
- ℹ️ About and contact pages
- 🔄 Fallback content when backend data is unavailable

👤 Patient Portal

- 📝 Patient registration and login
- 📅 Appointment booking
- 📋 Appointment history
- 🔎 Appointment status tracking
- 🔐 Authenticated patient access

🩺 Doctor Dashboard

- 🔑 Doctor login
- 📋 Assigned appointment review
- 👥 Patient list overview
- 🗓️ Schedule management
- ⏰ Availability management

🛡️ Admin Dashboard

- 👤 User monitoring
- 📅 Appointment management
- 🩺 Doctor account creation
- 🏥 Department management
- 📩 Contact message management
- ⚙️ Doctor and department availability management

🔐 Role-Based Access

User Role| Access
👤 Patient| Registration, login, appointment booking, and appointment tracking
🩺 Doctor| Dashboard, assigned appointments, patient overview, and schedules
🛡️ Admin| User monitoring, doctor and department management, and appointments

🛠️ Tech Stack

Technology| Purpose
⚛️ React.js| Frontend user interface
🧭 React Router| Client-side navigation
🔗 Axios| API communication
🟢 Node.js| Backend runtime
🚀 Express.js| Server and API framework
🍃 MongoDB| Database
🧩 Mongoose| Database modeling
🔐 Token-based authentication| User authentication
🌍 Vercel| Frontend deployment
☁️ Render| Backend deployment
🗄️ MongoDB Atlas| Cloud database hosting

📂 Project Structure

HealthNexus/
│
├── backend/
│   ├── middleware/
│   ├── models/
│   ├── seed/
│   ├── utils/
│   ├── authController.js
│   ├── authRoutes.js
│   ├── db.js
│   ├── portalController.js
│   ├── portalRoutes.js
│   ├── server.js
│   ├── siteController.js
│   ├── siteRoutes.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── auth/
│   │   ├── components/
│   │   ├── content/
│   │   ├── pages/
│   │   ├── api.js
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│   └── vercel.json
│
├── .gitignore
├── LICENSE
└── README.md

🚀 Installation

Prerequisites

Ensure the following tools are installed:

- "Node.js and npm" (https://nodejs.org/)
- "Git" (https://git-scm.com/)
- "MongoDB Atlas" (https://www.mongodb.com/atlas) or a local MongoDB instance

1️⃣ Clone the Repository

git clone https://github.com/YOUR-USERNAME/HealthNexus.git
cd HealthNexus

Replace "YOUR-USERNAME" with your repository owner's GitHub username.

2️⃣ Install Backend Dependencies

cd backend
npm install

3️⃣ Configure Environment Variables

Create a ".env" file inside the "backend" directory and add the variables required by your backend.

Example:

PORT=5000
MONGODB_URI=your_mongodb_connection_string

Add any other required authentication or configuration variables based on your code.

Security: Never upload real passwords, database credentials, API keys, or authentication secrets to GitHub.

4️⃣ Run the Backend

Use the command defined in "backend/package.json". For example:

npm start

Or, if available:

npm run dev

5️⃣ Install Frontend Dependencies

Open a new terminal at the project root:

cd frontend
npm install

6️⃣ Configure and Run the Frontend

Check "frontend/src/api.js" for the backend API configuration. Set it to your local backend address when running locally, if required.

Start the frontend using the command defined in "frontend/package.json", for example:

npm start

Or:

npm run dev

Open the local URL displayed in your terminal.

🌍 Deployment

The application can be deployed using the following services, depending on its current configuration:

- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

Configure the build commands, environment variables, backend API URL, and CORS settings for your deployment environment.

🔮 Future Enhancements

- 📧 Email and SMS appointment notifications
- 🎥 Online consultations
- 🔎 Advanced doctor search and filtering
- 📊 Appointment analytics and reporting
- 📱 Improved mobile responsiveness
- 🧪 Automated testing and monitoring

🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Full-stack application development
- REST API integration
- Database design and connectivity
- Authentication and role-based authorization
- Frontend and backend integration
- Git and GitHub version control
- Deployment configuration

👨‍💻 Author

PREETI KUMARI

- GitHub: https://github.com/Preetiikumari

📄 License

This project is licensed under the MIT License. See the "LICENSE" (LICENSE) file for details.

---

<p align="center">
  ⭐ If you find this project interesting, consider giving it a star!
</p>
