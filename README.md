# 🌍 ASTRASENSE

### AI-Powered Environmental Risk Intelligence Platform

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css"/>
  <img src="https://img.shields.io/badge/MapLibre-GIS-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI-Risk%20Analysis-orange?style=for-the-badge"/>
</p>

<p align="center">
  <strong>Transforming environmental data into actionable intelligence through AI-powered hazard prediction, geospatial analytics, and environmental monitoring.</strong>
</p>

<p align="center">
  <a href="https://astrasense-app.vercel.app">🌐 Live Demo</a> •
  <a href="https://github.com/MonaliPawar26/ASTRASENSE_Space">📂 Repository</a>
</p>

---

# 📖 Overview

**ASTRASENSE** is an advanced Environmental Intelligence Platform designed to simulate satellite-derived environmental indicators and convert them into meaningful hazard-risk assessments.

The platform combines:

* 🛰️ Geospatial Intelligence
* 🌱 Vegetation Monitoring
* 💧 Water Resource Analysis
* 🌡️ Land Surface Temperature Tracking
* 🤖 AI-Based Hazard Prediction
* 📊 Interactive Data Visualization

to provide environmental insights and support informed decision-making.

---

# ✨ Key Features

| Feature                  | Description                                                  |
| ------------------------ | ------------------------------------------------------------ |
| 🌍 Interactive 3D Globe  | Explore locations globally through immersive visualization   |
| 🔍 Smart Location Search | Hyperlocal environmental analysis using geocoding            |
| 📊 Risk Dashboard        | Real-time environmental indicators and analytics             |
| 🤖 AI Risk Engine        | Hazard probability prediction based on environmental metrics |
| 🗺️ GIS Mapping          | Spatial analysis with heatmaps and risk layers               |
| 🚨 Alert Center          | Severity-based environmental alert system                    |
| 📈 Trend Analysis        | Historical environmental data visualization                  |

---

# 🧠 Environmental Indicators

| Indicator | Full Form                              | Purpose                             |
| --------- | -------------------------------------- | ----------------------------------- |
| 🌱 NDVI   | Normalized Difference Vegetation Index | Measures vegetation health          |
| 💧 NDWI   | Normalized Difference Water Index      | Detects water presence and moisture |
| 🌿 EVI    | Enhanced Vegetation Index              | Advanced vegetation analysis        |
| 🌡️ LST   | Land Surface Temperature               | Surface heat monitoring             |

---

# 🤖 AI Hazard Prediction System

The simulation engine evaluates environmental indicators to estimate hazard probabilities.

| Hazard Type          | Detection Logic                      |
| -------------------- | ------------------------------------ |
| 🌊 Flood             | High NDWI values                     |
| ☀️ Drought           | High LST + Low NDWI                  |
| 🔥 Wildfire          | Extreme temperature + Dry conditions |
| 🌿 Vegetation Stress | Low NDVI                             |
| 🏜️ Land Degradation | Multi-factor environmental decline   |

---

# 📊 Project Highlights

| Metric                       | Value  |
| ---------------------------- | ------ |
| 🛰️ Environmental Indicators | 4      |
| 🚨 Hazard Categories         | 5      |
| 📍 Interactive Maps          | Yes    |
| 🌍 Global Search Support     | Yes    |
| 📈 Analytical Charts         | Yes    |
| 🤖 AI-Based Risk Analysis    | Yes    |
| 🚀 Deployment                | Vercel |

---

# 🏗️ System Architecture

```text
User Location Search
          │
          ▼
   Geocoding Service
          │
          ▼
 Environmental Engine
          │
 ┌────────┼────────┐
 ▼        ▼        ▼
Indices  Hazards  Alerts
          │
          ▼
 Risk Analysis Engine
          │
          ▼
 Interactive Dashboard
```

---

# 📂 Project Structure

```bash
src/
│
├── app/
│   ├── dashboard/
│   ├── map/
│   ├── alerts/
│   ├── about/
│   └── api/
│       ├── geocode/
│       └── simulate/
│
├── components/
│   ├── dashboard/
│   ├── alerts/
│   ├── charts/
│   ├── globe/
│   ├── map/
│   └── location/
│
├── hooks/
├── lib/
│   └── sim/
│
└── styles/
```

---

# ⚙️ Technology Stack

| Category            | Technologies                  |
| ------------------- | ----------------------------- |
| 🎨 Frontend         | Next.js 15, React, TypeScript |
| 💅 Styling          | Tailwind CSS                  |
| 🗺️ Mapping         | MapLibre GL JS                |
| 📈 Visualization    | Recharts                      |
| 🌍 Geocoding        | OpenCage API                  |
| 🔄 State Management | React Hooks                   |
| ☁️ Deployment       | Vercel                        |

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/MonaliPawar26/ASTRASENSE_Space.git

cd ASTRASENSE_Space
```

## 2️⃣ Install Dependencies

```bash
npm install
```

## 3️⃣ Configure Environment Variables

Create a `.env.local` file:

```env
OPENCAGE_API_KEY=your_api_key_here
```

## 4️⃣ Start Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

# 🎯 Use Cases

| Domain                      | Application                         |
| --------------------------- | ----------------------------------- |
| 🌍 Environmental Monitoring | Track ecological changes            |
| 🚨 Disaster Preparedness    | Early hazard identification         |
| 🏙️ Smart Cities            | Urban environmental planning        |
| 🌾 Agriculture              | Crop and vegetation monitoring      |
| 🌡️ Climate Research        | Environmental trend analysis        |
| 🎓 Education                | Learning and demonstration platform |

---

# 🔮 Future Roadmap

| Status      | Feature                         |
| ----------- | ------------------------------- |
| ✅ Completed | Interactive 3D Globe            |
| ✅ Completed | Environmental Dashboard         |
| ✅ Completed | AI Risk Prediction              |
| ✅ Completed | Alert Management System         |
| 🚧 Planned  | Real Satellite Data Integration |
| 🚧 Planned  | Machine Learning Forecasting    |
| 🚧 Planned  | Weather API Integration         |
| 🚧 Planned  | Advanced Climate Analytics      |
| 🚧 Planned  | Mobile Responsive Enhancements  |

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Developer

| Information     | Details                                           |
| --------------- | ------------------------------------------------- |
| 👩‍💻 Developer | Mona Pawar                                        |
| 🚀 Project      | ASTRASENSE                                        |
| 🌍 Domain       | Environmental Intelligence                        |
| 📂 Repository   | https://github.com/MonaliPawar26/ASTRASENSE_Space |
| 🌐 Live Demo    | https://astrasense-app.vercel.app                 |

---

<p align="center">
⭐ If you found this project useful, please consider giving it a Star on GitHub.
</p>

<p align="center">
Built with ❤️ using Next.js, TypeScript, AI, and Geospatial Intelligence.
</p>
