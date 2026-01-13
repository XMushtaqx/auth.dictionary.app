# Auth Dictionary App

A production-ready authentication-based dictionary web application built with **HTML, Tailwind CSS, and Vanilla JavaScript**, featuring OTP-based authentication, protected routes, and API-driven word definitions. The project is deployed on **Vercel** and follows a professional frontend workflow.

---

## 🚀 Live Demo

**Production URL:**
- https://auth-dictionary-app.vercel.app

---

## 📌 Features

- 🔐 **Authentication System**
  - Signup & Login flow
  - OTP verification
  - Client-side auth state handling

- 🛡 **Protected Routes**
  - Dashboard access restricted to authenticated users
  - Auth guard logic using `localStorage`

- 📖 **Dictionary Functionality**
  - Fetches word meanings using an external Dictionary API
  - Async/Await + Fetch API
  - Error handling for invalid or missing words

- 🎨 **UI & Styling**
  - Tailwind CSS for responsive and clean design
  - Mobile-friendly layout

- ☁️ **Deployment**
  - Deployed on Vercel
  - Continuous deployment via GitHub (main branch)

---

## 🧠 Tech Stack

- **Frontend:** HTML, Tailwind CSS, JavaScript (ES6+)
- **Async Handling:** Promises, Async/Await, Fetch API
- **Auth Simulation:** localStorage
- **Deployment:** Vercel
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
auth-dictionary-app/
│
├── index.html          # Login page (default entry)
├── signup.html         # Signup page
├── otp.html            # OTP verification page
├── dashboard.html      # Protected dashboard
│
├── js/
│   ├── auth.js         # Login & signup logic
│   ├── otp.js          # OTP verification logic
│   ├── auth-guard.js   # Route protection
│   ├── api.js          # Dictionary API handling
│   └── dashboard.js    # Dashboard logic
│
├── README.md
```

---

## ⚙️ How It Works

1. User signs up or logs in
2. OTP is generated and verified
3. Auth state is stored in `localStorage`
4. Auth guard prevents unauthorized access
5. Dictionary words are fetched asynchronously

---

## 🧪 Learning Outcomes

This project demonstrates:

- Real-world authentication flow (frontend simulation)
- Async programming with Promises and `async/await`
- API integration and error handling
- Route protection patterns
- Git conflict resolution & deployment workflow

---

## 📦 Setup (Local)

```bash
git clone https://github.com/XMushtaqx/auth.dictionary.app.git
cd auth.dictionary.app
```

Open `index.html` using Live Server or any local server.

---

## 👤 Author

**Mushtaq Ahmed**

- GitHub: https://github.com/XMushtaqx

---

## 📄 License

This project is for learning and educational purposes.

