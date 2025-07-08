
# 📚 Learning Management System (LMS)

A full-stack Learning Management System (LMS) web application built using the **MERN stack** (MongoDB, Express.js, React, and Node.js). The platform allows users to register, enroll in courses, and track their learning progress.

---

## 🚀 Features

- User Authentication (Student & Instructor roles)
- Course Listing, Enrollment, and Management
- Progress Dashboard (currently uses mock data)
- Payment UI (not yet connected to a gateway)
- Contact Form Page
- Responsive Design with Tailwind CSS
- RESTful API using Express.js

---

## 🖥️ Pages & Modules

- **Homepage**: Clean landing page with links to register/login
- **Courses Page**: Browse, view details, and enroll in courses
- **Login/Register**: Auth system for Students and Instructors
- **Progress Dashboard**: Shows mock progress (real-time tracking coming soon)
- **Contact Page**: Submit inquiries via a contact form (backend integration pending)
- **Payment Page**: UI-only for now (gateway integration planned)

---

## 🔧 Planned Improvements

- 🎥 Live Video Classes via Zoom/WebRTC
- 📊 Real-Time Progress Tracking (replace mock data)
- 🔔 Notifications & Email Reminders
- 💳 Payment Gateway Integration (e.g., Stripe, Razorpay)
- 📱 Mobile App (React Native)
- ☁️ Cloud Storage (Firebase / AWS S3)
- 🌐 Multi-language Support
- 🕹️ Gamification: Badges, Points, Leaderboards
- 📈 Analytics Dashboards for Students & Instructors
- 🔗 Google Classroom / Moodle Integration

---

## 📦 Tech Stack

- **Frontend**: React (Vite + TypeScript), Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Hosting**: Vercel (Frontend), Render (Backend)

---

## ⚙️ Environment Variables

Create a `.env` file in your backend directory with the following:

```env
DATABASE_URL=mongodb+srv://<username>:<password>@cluster0.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=your_jwt_secret_key_here_make_it_long_and_secure
PORT=5000
```

> 🔒 Replace `<username>` and `<password>` with your MongoDB Atlas credentials.

---

## 🛠️ Installation

```bash
# Clone the repository
git clone <repo-url>

# Navigate to backend and install dependencies
cd backendpart
npm install

# Start backend server
npm run dev

# In a separate terminal, navigate to frontend and install
cd ../frontendpart
npm install

# Start React app
npm run dev
```

---

## 📩 Contact

For questions or contributions, please reach out via the Contact Page or raise an issue on GitHub.

---

## 📜 License

MIT License – feel free to fork and build on this!
