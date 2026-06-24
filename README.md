<div align="center">

# 🧭 Uniway — MUJ Pathfinder

### Smart Campus Navigation for Manipal University Jaipur

![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white)

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Team](https://img.shields.io/badge/Team_Project-University-orange?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**A real-time, interactive campus navigation platform — built by students, for students.**

[🚀 Live Demo](https://uniway-se.vercel.app/) • [🎥 Watch Demo](https://drive.google.com/file/d/1AzWwHe1P1RrOsdv5PHjO4DqFKK8dhu50/view?usp=sharing&t=13) • [📂 Source Code](https://github.com/AasthaKapoor27/Uniway)

</div>

---

## 📌 Problem Statement

The Manipal University Jaipur campus is large and dynamic — making navigation challenging, especially for new students.

| Challenge | Impact |
|-----------|--------|
| No campus-specific navigation tool | Students waste time finding academic blocks & facilities |
| No real-time guidance | Confusion during first weeks of semester |
| Accessibility gaps | Differently-abled students face extra friction |

---

## 💡 What is Uniway?

Uniway is an **interactive campus navigation web app** that lets students explore MUJ's campus with real-time directions, digital maps, and a student-friendly interface. It goes beyond a simple map — it's a campus companion for daily academic life.

---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🗺️ Interactive Maps | Detailed digital campus map with landmarks and overlays via Leaflet.js |
| 📍 Real-time Location | Live tracking across campus buildings, hostels, and facilities |
| 🧭 Turn-by-Turn Directions | Step-by-step guidance to any campus destination |
| 360° Views | Official map integrations for immersive location previews |
| 🎓 Student Corner | Curated tips, cafes, events, and amenity discovery for new students |
| ♿ Accessibility | Navigation suggestions for smoother movement across campus |

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td><strong>Frontend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black" />
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Mapping & UI</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Leaflet.js-199900?style=flat-square&logo=leaflet&logoColor=white" />
      <img src="https://img.shields.io/badge/Lucide_React-F97316?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/React_Router_v7-CA4245?style=flat-square&logo=react-router&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Tooling & Dev</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/PostCSS-DD3A0A?style=flat-square&logo=postcss&logoColor=white" />
    </td>
  </tr>
</table>

---

## 🗂️ Project Structure

```
Uniway/
├── src/
│   ├── App.tsx              # Main app with all page components (~56KB)
│   ├── AppRouter.tsx        # React Router DOM routing setup
│   ├── StudentCorner.tsx    # Student resources & discovery page
│   ├── ComingSoon.tsx       # Placeholder for upcoming features
│   ├── main.tsx             # App entry point
│   └── index.css            # Global styles
├── index.html
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/AasthaKapoor27/Uniway.git

# Navigate into the project
cd Uniway

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## 🔮 Roadmap

- [ ] 🔐 Secure data handling with encryption
- [ ] 📅 Real-time class and lab availability tracking
- [ ] 📋 Timetable upload for personalized navigation
- [ ] 🔔 Smart alerts for upcoming classes
- [ ] 🏠 Hostel (GHS) navigation integration
- [ ] 📈 Improved mobile responsiveness and UX polish

---

## 🎥 Demo

> 📺 Click below to watch the full project walkthrough:

[![Demo Video](https://img.shields.io/badge/Watch_Demo-Google_Drive-blue?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com/file/d/1AzWwHe1P1RrOsdv5PHjO4DqFKK8dhu50/view?usp=sharing&t=13)

---

## 👩‍💻 Team

This is a team-developed academic project built at **Manipal University Jaipur**.

| Name | Role |
|------|------|
| **Aastha Kapoor** | Frontend Development, Routing, UI/UX |
| **Aarushi Shreevastava** | Maps Integration, Leaflet Implementation |
| **Rakshita Singh** | Student Corner, Feature Design |
| **Spriha Podder** | Accessibility, UX Research |

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center">

Made with ❤️ by students at Manipal University Jaipur

⭐ If you find this useful, give it a star!

</div>
