pitask/
├─ src/
│   ├─ components/
│   │   ├─ Home.jsx
│   │   ├─ TaskMarketplace.jsx
│   │   ├─ PostTask.jsx
│   │   ├─ Dashboard.jsx
│   │   ├─ ReferralCenter.jsx
│   │   ├─ AdminPanel.jsx
│   │   └─ WalletSimulator.jsx
│   ├─ backend/
│   │   ├─ taskService.js
│   │   └─ referralService.js
│   ├─ firebaseConfig.js
│   ├─ piWalletMock.js
│   └─ App.jsx
├─ package.json
├─ tailwind.config.js (optional)
└─ README.md (with setup steps)
# PiTask – Decentralized Task Marketplace on Pi Network

**PiTask** is a Web3-enabled decentralized microtask platform where users can earn Pi cryptocurrency for completing real-world tasks. Built with React, Firebase, and a mock Pi Network Wallet SDK integration, it also features a modular smart contract scaffold and an admin dashboard.

---

## 🌐 Live Demo
> _Coming soon: [https://pitask.vercel.app]_  

---

## 🔧 Features
- 🎯 Post & accept microtasks with Pi rewards
- 💰 Simulate Pi wallet transactions and balance updates
- 🛂 KYC badge indicator
- 🧑‍💼 Admin panel for moderation
- 🧪 Smart contract mock (escrow logic)
- ☁️ Firebase Firestore backend

---

## 📁 Folder Structure
```
src/
├── components/       # React components
├── backend/          # Firebase Firestore services
├── firebaseConfig.js # Firebase setup
├── piWalletMock.js   # Mock Pi Wallet SDK integration
└── App.jsx           # App routes
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/your-user/pitask.git
cd pitask
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Firebase
Create a `.env.local` file in the root directory:
```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

Edit `firebaseConfig.js` to import from `process.env`.

### 4. Run the App
```bash
npm start
```

---

## 🚀 Deployment

### Deploy to Vercel
1. Push to GitHub
2. Go to [Vercel](https://vercel.com), import the repo
3. Set environment variables (same as `.env.local`)
4. Deploy 🎉

### Deploy to Firebase Hosting
```bash
npm run build
firebase login
firebase init hosting
firebase deploy
```

---

## 📄 License
MIT License

---

## 🙌 Credits
- Designed by: Albert Rogers
- Developed with: React + Firebase
- Simulated by: OpenAI + Pi Wallet SDK Mock

> "Let Pi flow where effort goes."

