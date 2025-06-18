# 🔍 Hirred — Modern Job Portal

**Hirred** is a full-featured job portal built with modern web technologies. It offers a seamless experience for **candidates** to find jobs and for **recruiters** to post opportunities. With role-based authentication, clean UI, and real-time data, Hirred is optimized for performance, scalability, and ease of use.

---

## 🚀 Features

- 🔐 **Role-based Authentication** (Candidate / Recruiter) using [Clerk](https://clerk.dev)
- 🧑‍💼 **Recruiters** can post and manage job listings
- 🎯 **Candidates** can browse and apply to jobs
- 🔎 **Filter Jobs** by title, company, and location
- 🌍 **Dynamic Location Selector** with Country-State-City API
- ⚡ **Real-time Database** powered by [Supabase](https://supabase.io)
- 🎨 **Modern, Responsive UI** with [ShadCN UI](https://ui.shadcn.com) & Tailwind CSS

---

## 📸 Live Demo

👉 [https://your-live-demo-link.com](https://your-live-demo-link.com)

> *(Replace with your actual deployed link - Vercel or Netlify)*

---

## 🧑‍💻 Tech Stack

| Tech         | Purpose                        |
|--------------|--------------------------------|
| **React.js** | Frontend framework             |
| **Supabase** | Backend (PostgreSQL + APIs)    |
| **Clerk**    | Authentication & User Roles    |
| **Tailwind** | Styling (Utility-first CSS)    |
| **ShadCN UI**| Modern, accessible components  |
| **Country-State-City** | Location filtering   |

---

## 📁 Folder Structure

```
src/
├── api/              # Supabase API logic
├── components/       # Reusable UI components
├── hooks/            # Custom React hooks
├── pages/            # App pages (Home, JobList, etc.)
├── utils/            # Utility functions
└── assets/           # Icons, images, etc.
```

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/hirred-job-portal.git
cd hirred-job-portal
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Environment Variables

Create a `.env` file in the root directory and add:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

> ⚠️ Make sure `.env` is added to `.gitignore`

### 4. Run Locally

```bash
npm run dev
```

---

## 📦 Deployment

You can deploy this project easily on platforms like:

- [Vercel](https://vercel.com/)
- [Netlify](https://netlify.com/)
- [Render](https://render.com/)

Don’t forget to add environment variables in the hosting dashboard.

---

## 🧪 Future Improvements (Optional Ideas)

- ✅ Job Application Tracking System
- ✅ Admin Dashboard for Superuser
- ✅ Notifications for Candidate/Recruiter
- ✅ Resume Upload (PDF)
- ✅ Bookmark Jobs / Saved Jobs

---

---

## 🙋‍♂️ Author

**Devid Bisen**  
Frontend Developer  

📫 [LinkedIn](https://www.linkedin.com/in/devid-bisen/)  
🌐 [Portfolio](https://devidbisen.netlify.app/)

---

> ⭐️ If you like this project, please give it a star! It motivates continued development.
