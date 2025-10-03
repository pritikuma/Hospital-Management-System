# 🏥 Hospital Management System

A full-stack web application with **dual interfaces** for patients and admin.  

- **Patients** can book and track their visits.  
- **Admin** can manage schedules and monitor registered doctors with detailed information.  

---

## 🚀 Features

- 👩‍⚕️ **Doctor Management**: Admin can register, update, and manage doctor details.  
- 📅 **Appointments**: Patients can book and track appointments.  
- 🔑 **Authentication**: Secure login and signup using **JWT** & **Bcrypt** for password hashing.  
- 🌐 **Tech Stack**:  
  - **Frontend**: React.js  
  - **Backend**: Node.js, Express.js  
  - **Database**: MongoDB  
- 🔗 **CORS Enabled**: Smooth communication between frontend and backend.  

---

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system
# Go to backend folder
cd backend

# Install dependencies
npm install

# Create .env file and add the following variables
# (edit with your own values)
echo "PORT=5000
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-secret-key" > .env

# Start the backend server
npm start


# Open new terminal and go to frontend folder
cd frontend

# Install dependencies
npm install

# Start React app
npm start


