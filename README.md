# 🌙 MINDORA - The Lunar Writers Arena

> *Where Words Become Weapons & Writers Become Legends.*

[![Live Demo](https://img.shields.io/badge/Live-Demo-000000?style=for-the-badge&logo=firebase)](https://your-link.web.app)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-Auth%20%26%20Firestore-FFCA28?style=flat-square&logo=firebase)](https://firebase.google.com/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-3.0-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-white?style=flat-square)](LICENSE)

MINDORA is a dark, lunar-themed, competitive writing platform. It's not just a blogging site, it's a **Battle Arena** where writers compete in real-time Word Wars, get ranked on live leaderboards, and build their legacy.

---

## ✨ Live Demo
**[https://mindora-platform.web.app](https://mindora-platform.web.app)**

---

## 📸 Screenshots

| Landing Page (Lunar Theme) | Battle Arena | Writer Dashboard |
| :---: | :---: | :---: |
| Dark + Moon Aesthetic | Real-time Writing Battle | Stats & Writings |

---

## 🚀 Core Features

### 1. The Arena (Competitive Writing)
- **Word Wars:** 15-min, 30-min, 1-hour writing sprints
- **Live Ghost Writing:** See opponents' word count increasing in real-time
- **Anti-Cheat:** Tab-switch detection & copy-paste block

### 2. The Library (Publishing)
- **Rich Text Editor:** Medium-style editor with lunar dark mode
- **Genre System:** Fantasy, Sci-Fi, Horror, Poetry, etc.
- **Cover Generator:** Auto-generates aesthetic covers for stories

### 3. The Ranking System
- **Lunar Ranks:** New Moon -> Crescent -> Full Moon -> Blood Moon -> Eclipse
- **XP System:** +10 XP per 100 words, +50 XP for winning a battle
- **Global Leaderboard:** Daily, Weekly, All-time

### 4. Social & Community
- **Writer Clans:** Create or join writing guilds
- **Upvote & Eclipse:** Instead of like, you give "Eclipse"
- **Comments as Footnotes:** Aesthetic commenting system

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (Vite)
- TailwindCSS + Framer Motion for animations
- Lucide Icons
- React Router DOM

**Backend & Services:**
- Firebase Authentication (Google Auth)
- Cloud Firestore (Real-time Database)
- Firebase Hosting
- Firebase Storage (for covers)

**Deployment:** Firebase / Vercel

---

## 📁 Project Structure
/mindora-platform
├── /src
│   ├── /components
│   │   ├── /arena - Battle related components
│   │   ├── /editor - Rich text editor
│   │   ├── /layout - Navbar, Sidebar, Footer
│   │   └── /ui - Buttons, Modals (Lunar UI)
│   ├── /pages
│   │   ├── http://LandingPage.jsx
│   │   ├── http://ArenaPage.jsx
│   │   ├── http://LibraryPage.jsx
│   │   ├── http://ProfilePage.jsx
│   │   └── http://LeaderboardPage.jsx
│   ├── /hooks - useAuth, useBattle
│   ├── /lib - http://firebase.js
│   ├── http://App.jsx
│   └── http://main.jsx
├── /public
├── http://firebase.json
└── http://README.md

---

⚙️ Installation & Setup (Local)

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/your-username/mindora-platform.git
    cd mindora-platform
2.  *Install dependencies:*
    npm install
3.  *Setup Firebase:*
    - Go to Firebase Console -> Create Project `mindora-platform`
    - Enable Authentication (Google) & Firestore Database
    - Create `.env` file in root and add your keys:
    VITE_FIREBASE_API_KEY=your_api_key
    VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
    VITE_FIREBASE_PROJECT_ID=your_project_id
    VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
    VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
    VITE_FIREBASE_APP_ID=your_app_id
4.  *Run locally:*
    npm run dev
---

🗺️ Roadmap (Future Ideas)

- [ ] *AI Muse:* AI that gives you next line when you are stuck (but deducts XP)
- [ ] *Audio Tales:* Convert story to audio with AI voice
- [ ] *Collab Battles:* 2v2 writing battles
- [ ] *NFT Covers:* Mint your best story cover as NFT
- [ ] *Mobile App:* React Native version

---

🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are *greatly appreciated*.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

👩‍💻 Author

*Ayan / forida*
- GitHub: https://github.com/your-username
- Portfolio: http://your-portfolio.com

---

📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Built with 🌙 and late-night coffee by the MINDORA Team.*
