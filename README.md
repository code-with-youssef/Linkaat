# 🔒 Confidential Project Notice

⚠️ **This is a public showcase repository. The actual source code is private due to client confidentiality and production usage.**

If you're interested in learning more or discussing technical aspects of the implementation, feel free to reach out.

---

# 📱 Linkat — Social Page Builder for Creators

**Linkat** is a full-stack Laravel + React 19 project, designed to work as an extension of the [Future Dashboard](https://github.com/code-with-youssef/Future_dashboard), a dashboard system for managing creators' earnings, stats, and profiles.

This app allows content creators to build their personal **Link Page** — a public-facing page where they can add all their social media links, app promotions, and personal info for followers to access.

---

## 🚀 Tech Stack

- **Frontend**: React 19 (Vite + TypeScript)
- **Backend**: Laravel 12
- **Database**: MySQL
- **Deployment**: Live on cPanel (Production environment)
- **Auth System**: JWT-based via token from parent dashboard

---

## 🧩 Project Architecture

This project is not standalone. It connects to another project:

### 🔗 Integration with Future Dashboard

- Users are authenticated from the **Future Dashboard**.
- A button inside the dashboard passes a secure token to **Linkat**.
- Linkat decodes the token and gives the user access to edit or view their Link Page.

---

## 🌐 Core Features

### 🔸 Link Page for Creators

Each content creator has a dedicated page like:

https://liinkaat.com/youssefashraf


This page includes:
- Creator’s profile picture
- Bio / About section
- Social media icons and links
- Promoted applications (image, title, description, and link)

---

### ✍️ Creator Edit Mode

When the creator accesses Linkat via the secure token:
- They are redirected to an **Edit Mode** interface.
- Can upload/change their profile picture.
- Edit bio.
- Add/remove social media icons.
- Add/remove promoted app links with images and descriptions.

---

### 👀 Public View Mode

When a follower opens the creator’s page:
- They see a **read-only** version.
- No edit access.
- Clean and mobile-friendly interface.

---

## 🔐 Authentication & Security

- Linkat doesn’t implement its own login system.
- Instead, it relies on tokens generated from **Future Dashboard**.
- These tokens are used to:
  - Identify the user
  - Provide limited-time, secure access
  - Prevent unauthorized edits

---

## 📸 Screenshots (Replace with Real Images)
### 🖊️ Profile Edit

![Profile Edit](![alt text](image-3.png))
![Profile Edit - 2](![alt text](image-4.png))

---

### 📲 Apps Edit

![Apps Edit](![alt text](image-1.png))
![Apps Edit - 2](![alt text](image-2.png))

---

### 👀 Public View

![Public View](![alt text](image.png))
---

## 📂 Related Repositories

- [🔧 Future Dashboard (Admin Panel)](https://github.com/your-username/future-dashboard)  
  > The central dashboard managing creators, salaries, statistics, and authentication.

---

## 📢 Disclaimer

> This is a **production project** used by real users. The source code is **not included** in this repository. This README serves as a technical and functional overview only.

---

## 📬 Contact

If you'd like to learn more about the implementation, feel free to contact me:

- 📧 Email: your@email.com  
- 💼 LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-link)

---

"# Linkaat" 
