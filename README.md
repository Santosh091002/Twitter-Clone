# 🐦 Twitter Clone UI

A static, responsive clone of Twitter (X) built with **HTML** and **TailwindCSS** — focused purely on layout and design.  
This project replicates the look and feel of Twitter's dark theme using modern utility-first CSS with Tailwind.

---

## 🌐 Live Demo

🔗 [Live Demo](https://686695c873f7d00008121a9a--twitter-clone-free.netlify.app/)  

---

## 🚀 Features

- 🖼️ Pixel-perfect replica of Twitter’s web UI
- 🌓 Dark mode styling
- 📱 Fully **responsive layout** using Tailwind’s mobile-first classes
- 🔥 Sidebar with icons (Home, Explore, Notifications, etc.)
- 🗨️ Tweet input box and mock feed cards
- 📊 Trends and "Who to follow" panels

> ⚠️ Note: This is a **static clone** with **no JavaScript functionality** — ideal for UI prototyping.

---

## 🛠️ Built With

- HTML5
- TailwindCSS (via PostCSS or CDN)
- VS Code

---

## 📸 Preview

# Screenshot-1
![image](https://github.com/user-attachments/assets/27caf78f-c687-45fa-b93a-d98546ea9dcd)

# Screenshot-2
![image](https://github.com/user-attachments/assets/1a2d18f1-ce25-4b12-a8b0-d41b2b2de24e)

---

## 📁 Folder Structure

📦 TWITTER_CLONE
├── .vscode/ # VSCode settings (optional)
├── css/ # Tailwind CSS files
├── node_modules/ # Installed dependencies (if using Tailwind CLI)
├── index.html # Main entry point
├── package.json # Tailwind / PostCSS config
├── package-lock.json
└── README.md # Project documentation

---

## 📦 How to Run

### 👉 If you're just viewing the project:
```bash
# No setup needed
# Just open index.html in your browser

👉 If you're modifying the Tailwind styles:

# Install dependencies
npm install

# Rebuild Tailwind CSS when editing input.css
npx tailwindcss -i ./css/input.css -o ./css/output.css --watch


