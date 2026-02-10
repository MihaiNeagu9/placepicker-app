# Placepicker App

💎 **Bootcamp Project - React**

This learning project is a place picker application that allows you to choose places you want to visit. The goal of the project is to learn and practice dealing with Side Effects.

---

## 🧠 About the Project
This project is part of React Bootcamp. The main goal is to practice and understand React concepts of Side Effects (useEffect(), Dependencies). 

---

## 📚 What I Learned
Not yet added... 

---

## 🖼️ Screenshots

Screenshots coming soon...

---

## ⚙️ Features
- Displays a list of available places and a list of selected places
- Lets the user pick a place from the available list and adds it to the personal list
- Prevents adding the same place twice
- Allows initiating removal of a selected place (opens a confirmation modal)
- On confirm, removes the place from the personal list; on cancel, closes the modal without changes

---

## 🧩 Concepts Practiced
- Side Effects
- Dependencies

---

## 🛠️ Tech Stack
- React/Vite
- JavaScript
- HTML5
- CSS3

---

## 📂 Project Structure

```
11-side-effects/
├─ public/                      # Static assets served as-is
├─ src/
│  ├─ assets/                   # Image assets used in the UI
│  ├─ components/
│  │  ├─ DeleteConfirmation.jsx # Confirmation UI for deleting a selected place
│  │  ├─ Modal.jsx              # Reusable modal component (imperative open/close)
│  │  └─ Places.jsx             # Places list with selection handling + fallback text
│  ├─ App.jsx                   # App layout, state, and place selection/removal logic
│  ├─ data.js                   # Available places data
│  ├─ index.css                 # Global styles
│  ├─ loc.js                    # User/location utility (optional if unused)
│  └─ main.jsx                  # App entry point and React root mount
├─ .gitignore                   # Git ignore rules
├─ index.html                   # Vite HTML entry template
├─ package-lock.json            # Locked dependency versions
├─ package.json                 # Project metadata and scripts
├─ README.md                    # Project documentation
└─ vite.config.js               # Vite configuration
```
---

## 🔮 Possible Improvements
Not yet added...

---

## 🚀 Getting Started

### 1️⃣ Install dependencies
```bash
npm install
```

### 2️⃣ Start the dev server
```bash
npm run dev
```

Visit:
```
http://localhost:5173/
```