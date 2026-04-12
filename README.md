# Feastio: Smart Meal Planner

> AI-powered meal planning platform that generates personalized 7-day meal plans with detailed macros, ingredients and cooking time. Featuring a Gemini powered fitness assistant, adaptive recommendations based on diet, allergies, activity levels and menstrual health preferences, and auto-refreshing nutrition tips.
---

## Repositories

| Part | Repository |
|------|-----------|
| Frontend (React Native + Expo) | [FeastioApp](https://github.com/kartikey004/FeastioApp) |
| Backend (Node.js + Express) | [FeastioBackend](https://github.com/kartikey004/FeastioBackend) |

---
## Demo

▶️ [Watch Demo Video](https://drive.google.com/file/d/1oRLTmDGlXSF0xdBtI6XtLHaxFNvw2CdJ/view?usp=sharing)

---

## What is Feastio?

Feastio is a cross-platform mobile app that uses AI to generate personalized meal plans tailored to your diet preferences, allergies, activity levels, and health conditions.

Key highlights:
- **7-day AI meal plans** with ingredients, cook times, and macronutrient breakdowns
- **Gemini API** powered conversational health & fitness assistant
- **Auto-refreshing nutrition tips** - 5 new tips every 10 seconds
- **Menstrual health support** - personalized planning for Regular, Irregular, PCOS, and Menopause
- **Secure auth** via JWT + OTP email verification (Nodemailer)
- Adaptive personalization based on user profile

---

## Tech Stack

### Frontend
| Tech | Purpose |
|------|---------|
| React Native + Expo | Cross-platform mobile framework |
| TypeScript / JavaScript | Language |
| Redux | State management |
| React Navigation | Screen navigation |
| Axios | API communication |

### Backend
| Tech | Purpose |
|------|---------|
| Node.js + Express.js | Server & REST API |
| MongoDB | Database |
| Firebase | Additional services |
| JWT | Authentication |
| Nodemailer | OTP email verification |
| Gemini API | AI meal planning & health assistant |

---

## Setup Instructions

### 1. Clone both repositories

```bash
git clone https://github.com/kartikey004/FeastioApp.git
git clone https://github.com/kartikey004/FeastioBackend.git
```

### 2. Setup Backend

```bash
cd FeastioBackend
pnpm install        # or npm install

# Create a .env file and add your environment variables:
# MONGO_URI, JWT_SECRET, GEMINI_API_KEY, NODEMAILER credentials, FIREBASE config, etc.

pnpm dev            # development
node server.js      # production
```

### 3. Setup Frontend

```bash
cd FeastioApp
pnpm install        # or npm install

npx expo start      # development

npx expo build:android   # production (Android)
npx expo build:ios       # production (iOS)
```

> Make sure the backend is running and the API base URL is correctly set in the frontend config before starting the app.

---

## Project Structure Overview

```
Feastio/
├── FeastioApp/          # React Native mobile frontend
│   ├── api/             # API service layer
│   ├── app/             # App entry point
│   ├── components/      # Reusable UI components
│   ├── redux/           # State management
│   └── ...
│
└── FeastioBackend/      # Node.js REST API server
    ├── routes/          # API routes
    ├── controllers/     # Business logic
    ├── models/          # MongoDB schemas
    └── ...
```

---

## Contact

- **Email**: kartikeym004@gmail.com
- **LinkedIn**: [linkedin.com/in/kartikey004](https://www.linkedin.com/in/kartikey004/)
