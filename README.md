# 📋 Productivity Task Manager

A modern, fully client-side **task manager and productivity analytics dashboard** built with **plain HTML, CSS, and JavaScript**.  
No backend. No frameworks. No build tools.  
Designed to run perfectly on **GitHub Pages**.

---

## 🚀 Live Demo

After deployment:
https://<your-username>.github.io/<repository-name>/


---

## ✨ Features

### ✅ Task Management
- Create, complete, and manage tasks
- Due dates and categories
- Filters:
  - All tasks
  - Today
  - Overdue
  - Completed
- Persistent storage using browser `localStorage`

---

### 📊 Productivity Analytics
- **Completion Status Chart**
  - Completed vs Pending tasks
- **Weekly Productivity Chart**
  - Tasks completed per day (last 7 days)
- **Trend Line & Average**
  - Daily productivity with average reference line
- **Monthly Productivity Heatmap**
  - Visual activity intensity over the last 30 days
- **Streak Tracking**
  - Daily completion streak (Duolingo-style)
- **Time-to-Complete Analytics**
  - Average hours taken to complete tasks

All analytics update automatically when tasks change.

---

### 🌙 User Experience
- Dark mode toggle (saved across sessions)
- Responsive layout (desktop & mobile)
- Clean, card-based UI

---

### 🔔 Browser Notifications
- Optional notification permissions
- Alerts for tasks due today
- Uses native browser Notifications API
- No server required

---

### 📤 Data Management
- Export all tasks to a JSON file
- Import tasks from a JSON backup
- Useful for backups and migrations

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
  - CSS variables for theming
- **Vanilla JavaScript**
- **Chart.js (via CDN)**
- **Browser APIs**
  - localStorage
  - Notifications API
  - File API

---

## 📁 Project Structure

task-manager/
├── index.html
└── README.md


Only **one HTML file** is required to run the app.

---

## 🌍 Deploying to GitHub Pages

1. Create a new GitHub repository
2. Upload:
   - `index.html`
   - `README.md`
3. Go to **Settings → Pages**
4. Set:
   - Branch: `main`
   - Folder: `/root`
5. Save and wait ~30 seconds

Your site will be live 🎉

---

## 🧠 How Analytics Work

- Each task stores:
  - Creation timestamp
  - Completion timestamp
- Analytics are computed entirely in the browser:
  - Daily and weekly completions
  - Rolling averages
  - Completion streaks
  - Time-to-complete calculations
- Heatmap visualizes productivity density over time

No data ever leaves the browser.

---

## 🔐 Privacy

- No backend
- No accounts required
- No tracking
- No cookies
- All data remains local to the user

---

## 📈 Possible Future Improvements

- Progressive Web App (offline & installable)
- Cloud sync (Firebase / Supabase)
- Category-based analytics
- Drag-and-drop task ordering
- CSV export
- Multi-user authentication

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

## 👤 Author

**Harman Goraya**

A productivity-focused web application showcasing strong frontend fundamentals, analytics, and UI/UX design using vanilla technologies.

---

⭐ If you find this useful, consider starring the repository!
