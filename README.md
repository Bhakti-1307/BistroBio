# 🥗 Bistro Bio

**Bistro Bio** is an AI-powered *Bio-Steward* that helps users make healthier food choices in real-time.
Unlike traditional calorie trackers, Bistro Bio understands **why** you crave certain foods—by analyzing stress, sleep, habits, and context—and gently nudges you toward better decisions.

---

## 🚀 Problem Statement

Most health apps focus only on *what* you eat (calories), but ignore:

* emotional triggers
* stress and fatigue
* behavioral patterns

This leads to:

* inconsistent habits
* binge eating cycles
* guilt-driven tracking

**Bistro Bio solves this by being proactive, contextual, and non-judgmental.**

---

## 💡 Solution

Bistro Bio acts as a smart assistant that:

* predicts unhealthy cravings
* suggests better alternatives (“Smart Swaps”)
* provides emergency support during binge urges
* rewards recovery instead of punishing failure

---

## ✨ Key Features

### 🧠 Assistant-First Concierge

* AI-powered suggestions based on user behavior
* Real-time nudges for healthier decisions

### 🔄 Smart Swaps

* Suggests healthier alternatives when junk food is logged
* Explains *why* the swap is better

### 🚨 SOS Triage

* Emergency button for binge urges
* Provides:

  * distraction techniques
  * healthier high-volume alternatives

### 📍 Stealth Mode (Location-Aware)

* Suggests better menu choices when near restaurants

### 🌱 Bio-Garden Dashboard

* Visualizes internal health as a gamified system
* Encourages consistency through engagement

### 🔥 Phoenix System

* Non-punitive recovery mechanism
* Uses **Phoenix Tokens** to reset streaks without guilt

---

## 🏗️ Tech Stack

### Backend

* Python (FastAPI / Antigravity generated APIs)
* MongoDB Realm (formerly Stitch)

### Frontend

* HTML5, CSS3, JavaScript (Vanilla / React)

### Database

* MongoDB Atlas

### AI Integration

* OpenAI GPT / Vertex AI

### Infrastructure

* Google Cloud Platform (Cloud Run, Firestore)

---

## 🗄️ System Architecture

```id="a1b2c3"
User → Frontend UI → API Layer → Backend Logic → MongoDB Database
                         ↓
                      AI Engine
```

---

## 📊 Core Modules

* **User Management** → profiles, preferences
* **Behavior Tracking** → mood, sleep, cravings
* **Food Logging** → meal tracking + classification
* **Recommendation Engine** → Smart Swaps
* **SOS System** → emergency support
* **Recovery System** → Phoenix Tokens

---

## 🔌 API Endpoints

| Method | Endpoint      | Description               |
| ------ | ------------- | ------------------------- |
| POST   | /log-daily    | Log mood, stress, sleep   |
| POST   | /log-food     | Log food intake           |
| GET    | /suggest-swap | Get healthier alternative |
| POST   | /trigger-sos  | Activate SOS support      |
| GET    | /dashboard    | Fetch user insights       |

---

## 🔄 Workflow

1. User logs mood and food
2. System analyzes stress + behavior
3. AI predicts cravings
4. Smart Swap suggestions triggered
5. SOS system activates during high-risk moments
6. Phoenix system enables recovery

---

## 🛠️ Project Structure

```id="f7g8h9"
bistro-bio/
│
├── frontend/              # UI (React / HTML/CSS)
├── backend/               # API + logic
├── database/              # Schema & design
│
├── docs/
│   ├── bistro-bio-backend.md
│   ├── realm-prompt.md
│
└── README.md
```

---

## ⚙️ Setup (Conceptual)

1. Clone the repository
2. Set up the MongoDB Atlas database
3. Configure MongoDB Realm (collections, functions, triggers)
4. Run backend server
5. Launch frontend

---

## 🌍 Future Enhancements

* Wearable integration (HRV, sleep tracking)
* Real-time GPS-based suggestions
* Receipt scanning for food tracking
* Advanced AI habit prediction

---

## 🎯 Vision

To create a **human-like AI companion** that:

* understands behaviour, not just data
* supports users without judgment
* builds sustainable health habits

---

## 🤝 Contribution

This project is currently in development. Contributions, ideas, and feedback are welcome.

---

## 🙌 Acknowledgment

Built as part of a Promptathon project to explore AI-driven behavioral health solutions.
