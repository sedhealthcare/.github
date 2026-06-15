# SedHealthcare

A comprehensive healthcare platform with web and mobile applications.

## 📱 Projects

| Project | Purpose | Status |
|---------|---------|--------|
| [sedhealthcare-backend](https://github.com/sedhealthcare/sedhealthcare-backend) | Express API + MongoDB | Live on Render |
| [sedhealthcare-frontend](https://github.com/sedhealthcare/sedhealthcare-frontend) | React web + Capacitor mobile | Live on Play Store (APK) |

## 🚀 Quick Start

### Backend
```bash
cd backend
npm install
npm run dev
```
Runs on `http://localhost:5001`

### Frontend (Web)
```bash
cd frontend
npm install
npm run dev
```
Runs on `http://localhost:5173`

### Frontend (Android)
```bash
cd frontend
npm run build
npx cap sync
cd android
./gradlew assembleDebug
```
APK: `android/app/build/outputs/apk/debug/app-debug.apk`

## 📋 Features

- **Patient Portal**: Login, search doctors, book appointments, lab tests, pharmacy
- **Admin Dashboard**: Manage doctors, appointments, lab tests, pharmacy inventory
- **Mobile App**: Full-featured Android app 
- **Real-time Sync**: Changes sync between web and mobile instantly

## 🛠 Tech Stack

- **Frontend**: React 18, Vite, Tailwind CSS, Framer Motion
- **Mobile**: Capacitor (Android + iOS)
- **Backend**: Node.js, Express, MongoDB Atlas
- **Deployment**: Render (backend), Vercel/APK (frontend)

## 📝 License

All rights reserved. Private project.

## 👨‍💻 Author

**Abdullah** — Junior QA

---

For issues, contributions, or questions → create an issue in the relevant repo.
EOF
