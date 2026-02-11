# Placepicker App

💎 **Bootcamp Project - React**

This learning project is a place picker application that allows you to choose places you want to visit. The goal of the project is to learn and practice dealing with Side Effects.

---

## 🧠 About the Project
This project is part of React Bootcamp. The main goal is to practice and understand React concepts of Side Effects (useEffect(), Dependencies). 

---

## 📚 What I Learned
A side effect is a piece of code that does not influence the rendering process of the respective component. An example of a side effect is trying to get the user's location. I tried to do this with the getCurrentPosition function to sort the places in the application in ascending order according to the user's location. I used the useEffect() hook because the piece of code for locating the user did not affect the App component and to avoid an infinite loop caused by updating the state.

I don't always have to use useEffect for a side effect. It is recommended to use useEffect when the code is asynchronous, executing later than the rest of the code. If the code runs instantly, there is no need to use useEffect (localStorage to fetch data).

Dependencies (the second parameter of useEffect) are used when I want to run the piece of code inside the function based on a value that changes (open state).

---

## 🖼️ Screenshots

Screenshots coming soon...

---

## ⚙️ Features
- Displays a list of available places and a list of selected places
- Lets the user pick a place and add it to the personal list
- Prevents duplicates
- Opens a confirmation modal before deleting a selected place
- Auto-delete: if the user does nothing for 3 seconds, the selected place is removed automatically
- Cancel closes the modal without changes

---

## 🧩 Concepts Practiced
- Side Effects (`useEffect`)
- Effect cleanup
- Dependency arrays
- Timers (`setTimeout`)

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
│  │  ├─ ProgressBar.jsx        # Reusable progress bar component
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
- Add tests for auto-delete timer and cleanup
- Replace timers with a visible countdown
- Improve accessibility on the modal

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