# 📝 delor notlar

**delor notlar** is a sleek, real-time shared notepad application built with a modern "Tech-Noir" aesthetic. It allows users to post thoughts, notes, or messages instantly to a public feed using a high-performance Firebase backend.

![Version](https://img.shields.io/badge/version-2.0-blue)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)
![TailwindCSS](https://img.shields.io/badge/Styling-TailwindCSS-38B2AC)

---

## ✨ Features

* **Real-time Updates:** Messages appear instantly across all devices without refreshing, powered by Firebase Firestore's `onSnapshot` listener.
* **Modern UI/UX:** A "Glassmorphism" design featuring deep gradients, frosted glass panels, and smooth hover animations.
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing using Tailwind CSS.
* **Interactive Elements:**
    * Glass-textured input fields with focus effects.
    * Dynamic hover states and transitions for note cards.
    * Integrated deletion system for easy note management.
* **Lightweight Architecture:** Built entirely with a modular CDN approach—no heavy `node_modules` installation required.

---

## 🚀 Tech Stack

* **Frontend:** HTML5 & Tailwind CSS
* **Fonts & Icons:** Plus Jakarta Sans (Google Fonts) & Font Awesome 6
* **Database:** Google Firebase Firestore (NoSQL)
* **Logic:** Modular JavaScript (ES6+)

---

## 🛠️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/delor-notlar.git](https://github.com/your-username/delor-notlar.git)
    ```

2.  **Configure Firebase:**
    Open `derlor.html` and locate the `firebaseConfig` object. The project is currently configured with a specific project ID (`project1-2838d`). To use your own database, replace the values in the config block:
    ```javascript
    const firebaseConfig = {
      apiKey: "YOUR_API_KEY",
      authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
      projectId: "YOUR_PROJECT_ID",
      storageBucket: "YOUR_PROJECT_ID.firebasestorage.app",
      messagingSenderId: "YOUR_SENDER_ID",
      appId: "YOUR_APP_ID"
    };
    ```

3.  **Run the App:**
    Simply open `derlor.html` in any modern web browser—no local server setup is strictly required for the frontend.

---

## 📸 Interface Details

* **Theme:** Midnight Navy (`#0f172a`) with Electric Blue (`#3b82f6`) accents.
* **Branding:** Personalized as **delor notlar** with a "Kişisel Paylaşım Alanı" subtitle.
* **Components:**
    * **Header:** Features a vibrant Indigo-to-Blue gradient.
    * **Feed:** A scrollable container with custom-styled scrollbars for a consistent look across browsers.

---

## 📜 License

This project is open-source. Feel free to fork it and customize your own personal sharing space.

---
**v2.0 // delor system**
