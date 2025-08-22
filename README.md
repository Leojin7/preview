<!-- LUMINA LOGO: Use a scalable SVG/logo in your actual repo. Placeholder below. -->
<h1 align="center">
  <img src="https://svgshare.com/i/15fC.svg" width="120" alt="Lumina Logo"/><br />
  <span style="font-family: 'Inter', sans-serif; font-weight: 900; font-size: 3rem; color: #6F5BFF; letter-spacing: 2px;">Lumina</span>
  <br /><span style="font-size: 1.15rem; color: #8A8DF9;">AI-Powered Study Platform</span>
</h1>

<p align="center">
  <em>Modern, collaborative, and intelligent learning — design meets AI.<br>
  Beautifully crafted by engineers for inspiring minds.</em>
</p>

<div align="center" style="margin: 2rem 0;">
  <img src="https://github.com/leojin7/preview/assets/banners/lumina-demo.gif" alt="Lumina Demo GIF" width="92%">
</div>

---

<p align="center">
  <img src="https://img.shields.io/github/stars/Leojin7/preview?style=for-the-badge&color=f3e7ff" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/Leojin7/preview?style=for-the-badge&color=a5b4fc" alt="Forks"/>
  <img src="https://img.shields.io/github/license/Leojin7/preview?style=for-the-badge&color=6d28d9" alt="license"/>
  <img src="https://img.shields.io/badge/Made_with-TypeScript-3178c6?style=for-the-badge&logo=typescript" alt="TypeScript"/>
</p>

---

## 🎨 Theme

- **Colors:**  
  ![#6F5BFF](https://via.placeholder.com/15/6F5BFF/000000?text=+) `#6F5BFF` — Indigo Accent  
  ![#8A8DF9](https://via.placeholder.com/15/8A8DF9/000000?text=+) `#8A8DF9` — Soft Violet  
  ![#232946](https://via.placeholder.com/15/232946/000000?text=+) `#232946` — Deep Navy  
  ![#F3F6FD](https://via.placeholder.com/15/F3F6FD/000000?text=+) `#F3F6FD` — Clean White  
  ![#FFB5A7](https://via.placeholder.com/15/FFB5A7/000000?text=+) `#FFB5A7` — Focus Red

- **Font:**  
  Primary: `Inter` (fallback: `sans-serif`), designed for clarity and beauty.

- **Animation:**  
  Smooth interactions and transitions powered by **Framer Motion** for an elegant, lively experience.

---

## 🚀 Features

- <strong>Squad Rooms</strong>: Real-time collaborative study sessions, chat, and synchronized Pomodoro timers
- <strong>AI Quizzes</strong>: Dynamic quiz generation with Gemini AI
- <strong>Focus Tracking</strong>: Pomodoro workflow, session analytics
- <strong>Wellness Dashboard</strong>: Digital wellbeing and mindfulness tools
- <strong>Portfolio Showcase</strong>: LeetCode integration and project displays
- <strong>Coding Arena</strong>: Interactive coding challenges and playground

<div align="center" style="margin: 2rem 0;">
  <img src="https://github.com/leojin7/preview/assets/screenshots/lumina-focus.gif" width="94%" style="border-radius: 12px;" alt="Focus Feature Animation">
</div>

---

## 🛠️ Tech Stack

| Layer        | Technology                        |
| ------------ | -------------------------------- |
| Frontend     | React 18, TypeScript, Tailwind CSS |
| State        | Zustand (w/ persistence)          |
| Database     | Firebase Realtime Database        |
| Auth         | Firebase Auth                    |
| AI           | Google Gemini API                 |
| Build Tool   | Vite                              |
| Animation    | Framer Motion                     |

---

## 📦 Installation

<details>
  <summary><b>Expand to get started</b></summary>
<br>

### <span style="color:#6F5BFF">Prerequisites</span>
- Node.js v16+

### <span style="color:#6F5BFF">Clone and setup</span>

git clone https://github.com/Leojin7/preview.git
cd preview
npm install

text

### <span style="color:#6F5BFF">Environment Variables</span>

- Copy `.env.local.example` to `.env.local`
- Add your Gemini API key:
GEMINI_API_KEY=your_gemini_api_key_here

text

### <span style="color:#6F5BFF">Firebase Config</span>
- Update Firebase config in `index.html`  
- Make sure **Firebase Realtime Database** and **Auth** are enabled

### <span style="color:#6F5BFF">Dev Server</span>
npm run dev

text
</details>

---

## 🏗️ Project Structure

src/
├── components/ # Reusable UI blocks
│ ├── portfolio/ # For portfolio & LeetCode features
│ ├── wellness/ # Mindfulness & wellness features
│ └── ...
├── pages/ # Main app pages
├── stores/ # Zustand state logic
├── services/ # API integrations
├── constants/ # Shared constants
└── types.ts # TypeScript interfaces

text

---

## 🔥 Key Features Implemented

### <span style="color:#6F5BFF">Squad Rooms</span>
- Secure, real-time collaboration (Firebase)
- Encrypted chat
- Synced pomodoro/focus timers
- Host controls & member management

### <span style="color:#6F5BFF">AI Integration</span>
- Gemini-driven quiz generation
- Dynamic question/answer interaction

### <span style="color:#6F5BFF">State & UX</span>
- Persistent global state (Zustand)
- Real-time updates, optimistic UI
- Framer Motion animation

---

## 🚀 Deployment

Ready for modern hosts.  
Build and deploy your app:

npm run build

text

---

## 🤝 Contributing

We 💜 contributors! Here's how you can make this project better:

1. Fork this repo
2. Create your feature branch
3. Commit your changes
4. Push and submit a pull request

---

## 📄 License

MIT

---

<div align="center" style="margin: 2rem 0;">
  <img src="https://github.com/leojin7/preview/assets/banners/lumina-animated.gif" width="80%" alt="Lumina Animation Banner">
</div>

---

<p align="center" style="color:#232946; font-size:1.2rem;">
  <b>Beautiful code, crafted experiences, next-gen learning.<br/>Welcome to Lumina.</b>
</p>
