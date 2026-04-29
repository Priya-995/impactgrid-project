<div align="center">

<br/>

```
██╗███╗   ███╗██████╗  █████╗  ██████╗████████╗ ██████╗ ██████╗ ██╗██████╗
██║████╗ ████║██╔══██╗██╔══██╗██╔════╝╚══██╔══╝██╔════╝ ██╔══██╗██║██╔══██╗
██║██╔████╔██║██████╔╝███████║██║        ██║   ██║  ███╗██████╔╝██║██║  ██║
██║██║╚██╔╝██║██╔═══╝ ██╔══██║██║        ██║   ██║   ██║██╔══██╗██║██║  ██║
██║██║ ╚═╝ ██║██║     ██║  ██║╚██████╗   ██║   ╚██████╔╝██║  ██║██║██████╔╝
╚═╝╚═╝     ╚═╝╚═╝     ╚═╝  ╚═╝ ╚═════╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚═╝╚═════╝
```

### **AI-Powered Decision Intelligence for Crisis Response**
*Turning community needs into coordinated, intelligent action — in real time.*

<br/>

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-impactgrid.vercel.app-22c55e?style=for-the-badge&logoColor=white)](https://impactgrid-project.vercel.app/)
[![React](https://img.shields.io/badge/React-Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<br/>

> **Every second matters in a crisis. ImpactGrid makes those seconds count.**

<br/>

---

</div>

## 🌍 The Problem We're Solving

When floods hit, when medical emergencies surge, when resources run dry — **help exists, but it doesn't reach people in time**.

Volunteers are ready. Supplies are available. Organizations are willing.

Yet the coordination layer fails. Urgency is misread. The wrong volunteers are dispatched. Critical information drowns in WhatsApp threads.

**The cost? Lives.**

```
❌  Manual coordination   →   Hours of delay
❌  No prioritization     →   Wrong cases attended first
❌  Blind assignments     →   Mismatched volunteers
❌  Zero transparency     →   No accountability
```

---

## ⚡ Enter ImpactGrid

ImpactGrid is a **Decision Intelligence Platform** that sits between crisis and response — acting as the coordination brain that humans can't always be under pressure.

```
CRISIS REPORTED  →  AI ANALYZES  →  BEST MATCH FOUND  →  EXPLAINED  →  ACTION TAKEN
```

We don't just assign volunteers. We **explain why**, ensuring trust, transparency, and smarter decisions at every step.

---

## 🧠 How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                        IMPACTGRID FLOW                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   [Case Reported]                                               │
│        │                                                        │
│        ▼                                                        │
│   [Urgency Evaluation Engine]  ──→  Priority Score Assigned     │
│        │                                                        │
│        ▼                                                        │
│   [Smart Matching Engine]                                       │
│        ├──  Skill Compatibility     (weight: 40%)               │
│        ├──  Proximity / Location    (weight: 25%)               │
│        ├──  Availability Window     (weight-25%)                │
│        └──  Case Category Match     (weight: 10%)               │
│        │                                                        │
│        ▼                                                        │
│   [Explainability Layer]  ──→  Human-readable reasoning output  │
│        │                                                        │
│        ▼                                                        │
│   [AI Insight Engine]  ──→  Operational recommendations         │
│        │                                                        │
│        ▼                                                        │
│   [Volunteer Dispatched + Case Tracked]                         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🔥 Key Features

### 📌 Case Reporting System
Structured intake form capturing severity, category, location, and resource needs — fed directly into the prioritization engine.

### 🙋 Volunteer Registration & Profiles
Volunteers register with skills, availability, and preferred case types. This becomes the input layer for intelligent matching.

### 🔍 Explainable Matching Engine *(Core Innovation)*
Unlike black-box systems, ImpactGrid tells you **exactly** why a volunteer was chosen:

```yaml
Volunteer: Priya Sharma
Match Score: 87%

Reasoning:
  ✅ Skill Match:       Medical First Aid + Flood Rescue    → +40pts
  ✅ Proximity:         2.1 km from incident location       → +25pts
  ✅ Availability:      Available immediately               → +25pts
  ✅ Category Fit:      Preferred: Medical Emergencies      → +10pts - 13pts deducted (partial skill gap)

Decision: BEST AVAILABLE MATCH — Dispatching now.
```

> Transparency builds trust. Trust drives faster action.

### 🤖 AI Operations Insight Engine
Powered by **Grok API**, ImpactGrid generates real-time operational intelligence:
- 🔴 Identifies high-priority clusters of cases
- 📋 Suggests NGO actions based on active case load
- 📊 Surfaces patterns in crisis data for predictive awareness

### 🔄 Real-Time Dashboard
A live coordination view for NGO operators — active cases, volunteer statuses, assignments, and AI recommendations in one unified screen.

---

## 🏗️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | React (Vite) + TypeScript | Fast, type-safe UI |
| **Styling** | Tailwind CSS | Utility-first responsive design |
| **Backend** | Node.js + Express.js | RESTful API server |
| **Database** | MongoDB + Mongoose | Flexible schema for dynamic case/volunteer data |
| **AI Layer** | Grok API | Operational insights & recommendations |
| **Deployment** | Vercel (FE) + Render (BE) | Scalable, zero-downtime hosting |

---

## 🚀 Getting Started

### Prerequisites

```bash
node >= 18.x
npm >= 9.x
MongoDB (local or Atlas)
```

### Clone & Install

```bash
# Clone the repository
git clone https://github.com/your-username/impactgrid.git
cd impactgrid

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

### Environment Setup

Create a `.env` file in `/server`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
GROK_API_KEY=your_grok_api_key
```

Create a `.env` file in `/client`:

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

### Run Locally

```bash
# Start backend
cd server
npm run dev

# Start frontend (new terminal)
cd client
npm run dev
```

Visit `http://localhost:5173` 🎉

---

## 📂 Project Structure

```
impactgrid/
├── client/                  # React + Vite Frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Dashboard, Cases, Volunteers
│   │   ├── hooks/           # Custom React hooks
│   │   └── utils/           # Helpers & API calls
│   └── ...
│
├── server/                  # Node.js + Express Backend
│   ├── controllers/         # Route logic
│   ├── models/              # Mongoose schemas
│   ├── routes/              # API endpoints
│   ├── services/
│   │   ├── matchingEngine/  # Core smart matching logic
│   │   └── aiInsights/      # Grok API integration
│   └── ...
│
└── README.md
```

---

## 🌍 Real-World Impact

> Even a **10-minute reduction** in emergency response time can increase survival rates by up to **40%** in critical medical scenarios.

ImpactGrid is designed to compress that gap — through automation, intelligence, and transparency.

```
⏱  Faster response         →  More lives saved
📦  Better resource use    →  Less waste, more reach
🤝  Smarter coordination   →  Less burnout for NGOs
🧠  Explainable decisions  →  Greater community trust
```

---

## 🎯 UN SDG Alignment

| Goal | Connection |
|------|-----------|
| 🏥 **SDG 3** — Good Health & Well-being | Faster medical emergency response |
| 🏙 **SDG 11** — Sustainable Cities | Resilient, coordinated urban crisis management |
| 🌱 **SDG 13** — Climate Action | Adaptive tools for climate-induced disasters (floods, heatwaves) |

---

## 🔭 Roadmap

```
✅ MVP — Case management, smart matching, AI insights
🔲 v1.1  — Predictive crisis detection using historical data
🔲 v1.2  — Government & NGO API integrations
🔲 v1.3  — Real-time SMS/push alert system
🔲 v2.0  — Native mobile application (React Native)
🔲 v2.5  — Fully automated decision pipelines with human-in-loop fallback
```

---

## 🤝 Contributing

We welcome contributors who care about technology for good.

```bash
# Fork the repo
# Create your feature branch
git checkout -b feature/your-feature-name

# Commit changes
git commit -m "feat: add your feature"

# Push and open a PR
git push origin feature/your-feature-name
```

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting PRs.

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

<div align="center">

<br/>

**Built with purpose. Powered by AI. Driven by impact.**

*ImpactGrid — because coordination shouldn't be the bottleneck in a crisis.*

<br/>

[![Live Demo](https://img.shields.io/badge/🚀%20Try%20It%20Live-impactgrid--project.vercel.app-22c55e?style=for-the-badge)](https://impactgrid-project.vercel.app/)

<br/>

⭐ **Star this repo if you believe technology can save lives** ⭐

</div>
