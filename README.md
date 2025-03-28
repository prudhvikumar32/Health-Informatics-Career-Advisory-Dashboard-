
# 🧠 Health Informatics Career Advisory Dashboard  
*Empowering careers through data-driven insights into the health informatics job market.*

---

## 📘 Project Description

This project is a full-stack web application designed to assist career advisors, healthcare professionals, and HR recruiters in navigating the evolving health informatics job market. It integrates real-world and simulated data sources to deliver interactive analytics on:

- Job role demand
- Salary benchmarks
- Required skills and certifications
- Location-wise opportunities
- Forecasting of workforce needs

🚧 **Note**: Development is in progress. This repository reflects the project roadmap, draft visualizations, and design prototypes. Implementation will use **React (frontend)** and **Node.js (backend)**.

---

## 📑 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Screenshots](#screenshots)
- [Live Dashboard (Coming Soon)](#live-dashboard-coming-soon)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 🛠 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/health-informatics-dashboard.git
cd health-informatics-dashboard
```

2. Install frontend dependencies:

```bash
cd client
npm install
```

3. Install backend dependencies:

```bash
cd ../server
npm install
```

4. Set up environment variables:

Create a `.env` file in `/server` with your MongoDB URI, API keys, etc.

```env
PORT=5000
MONGO_URI=mongodb+srv://your_mongodb_uri
```

5. Start development servers:

```bash
# Start backend
cd server
npm start

# Start frontend (in another terminal)
cd client
npm start
```

---

## 🚀 Usage

Once both servers are running:

- Access the site at `http://localhost:3000`
- The backend runs at `http://localhost:5000`
- React will proxy API requests to the Node.js server

---

## 🗂 Project Structure

```bash
health-informatics-dashboard/
├── client/                # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
├── server/                # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
├── assets/                # Screenshots, mockups
├── README.md
└── .gitignore
```

---

## ✨ Features

- 📊 Role-specific job demand and salary analytics
- 🌍 Regional distribution of jobs in health informatics
- 🧠 AI-driven skill gap and role forecasting (planned)
- 📌 Real-time filtering by role, location, skillset
- 📈 Integrated Power BI dashboards (in later phase)
- 🔐 Scalable RESTful API backend
- 📁 Clean, modular React component architecture

---

## 🖼 Screenshots

### 🔹 Role Analytics (Draft)
![Role Analytics Screenshot](assets/role-analytics.png)

### 🔹 Skill Gap Visuals (Draft)
![Skill Gap Draft](assets/skill-gap-draft.png)

### 🔹 Dashboard Preview (Power BI Draft)
![Power BI Dashboard](assets/powerbi-preview.png)

> These screenshots are based on design drafts presented during Week 8.

---

## 📊 Live Dashboard (Coming Soon)

Interactive Power BI & web-based dashboard will be hosted on:
👉 [https://yourusername.github.io/health-informatics-dashboard](https://yourusername.github.io/health-informatics-dashboard)

> *Dashboard is under construction. Placeholder screenshots included.*

---

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you'd like to change.

Want to help?
- Submit job datasets or mock data
- Share feedback on UX/UI design
- Suggest useful roles or metrics

---

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

- **Professor Maria Weber** – Project Supervisor
- **Synthea** – For simulated patient data
- **Team 14 Members**:
  - Jalandhar Bollam
  - Prudhvi Kumar Borigam
  - Srinivas Bandaru
  - Abhinay Basani
  - Krishna Teja Reddy Gurijala
- Tools Used:
  - Power BI
  - React
  - Node.js
  - Draw.io
  - Figma (for design drafts)
