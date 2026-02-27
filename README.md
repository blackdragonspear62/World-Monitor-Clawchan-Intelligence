<div align="center">

<img src="docs/presentations/clawchan-cover.png" width="100%" alt="Clawchan Intelligence Agency">

# 🌍 WORLD MONITOR v2
## CLAWCHAN INTELLIGENCE AGENCY

[![TypeScript](https://img.shields.io/badge/TypeScript-49%20files-blue?logo=typescript)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://reactjs.org/)
[![Three.js](https://img.shields.io/badge/Three.js-3D%20Globe-black?logo=three.js)](https://threejs.org/)
[![Vite](https://img.shields.io/badge/Vite-Build%20Tool-646CFF?logo=vite)](https://vitejs.dev/)
[![Tailwind](https://img.shields.io/badge/Tailwind-CSS-06B6D4?logo=tailwindcss)](https://tailwindcss.com/)
[![Zustand](https://img.shields.io/badge/Zustand-State%20Management-FF6B6B)](https://github.com/pmndrs/zustand)

**Real-time Global Intelligence Dashboard with Bloomberg Terminal-style Interface**

[🌐 Live Demo](https://g5dg7g55gd4ze.ok.kimi.link) • [📊 Architecture](#architecture) • [🚀 Getting Started](#getting-started)

</div>

---

## 📊 Repository Statistics

| Metric | Value |
|--------|-------|
| **Total Files** | 84 files |
| **TypeScript** | 49 files (Frontend + Node.js Backend) |
| **Python** | 2 files (ML Models) |
| **Go** | 2 files (Security + WebSocket) |
| **Rust** | 1 file (High-Performance Core) |
| **Java/Kotlin** | 2 files (Ingestion Service) |
| **Scala** | 1 file (Stream Analytics) |
| **C++** | 1 file (Ultra-Low-Latency Engine) |

---

## ✨ Features

### 🎯 11 Live Intelligence Widgets

<img src="docs/presentations/clawchan-global.png" width="100%" alt="Dashboard Overview">

| Widget | Description | Data Source |
|--------|-------------|-------------|
| 🌍 **Global Intelligence** | 3D Earth globe with Google Earth AI visualization | Three.js |
| ✈️ **ADS-B Tracking** | Real-time aircraft tracking (8,000+ aircraft) | ADS-B Exchange |
| 🛰️ **Satellite Tracking** | ISS, Starlink, GPS, HST, NOAA satellites | N2YO |
| 📈 **Global Markets** | S&P 500, Dow Jones, NASDAQ, VIX | Yahoo Finance |
| ₿ **Cryptocurrency** | BTC, ETH, SOL, XRP live prices | CoinGecko |
| 📰 **Intelligence Feed** | Multi-source news aggregation | Guardian API |
| 🌤️ **Global Weather** | 6 major cities weather monitoring | OpenWeatherMap |
| 🌋 **Seismic Monitor** | USGS earthquake alerts | USGS |
| 🛡️ **Cyber Security** | Threat intelligence & monitoring | Internal |
| 🚢 **Maritime AIS** | Vessel tracking worldwide | AIS |
| 📡 **SIGINT Collection** | Signal intelligence & frequency scanning | Internal |

---

## 🎨 Bloomberg Terminal UI

<img src="docs/presentations/clawchan-terminal.pptx.html" width="100%">

### Design Features
- ✅ **Grid Layout** - 4-column responsive widget system
- ✅ **Navigation Tabs** - ALL, INTEL, TRACKING, FINANCE, SECURITY
- ✅ **Live Indicators** - Green pulsing dots on all widgets
- ✅ **Status Bar** - Real-time system metrics & data sources
- ✅ **Dark Theme** - Professional terminal aesthetic

---

## 🛰️ 3D Globe Visualization

<img src="docs/presentations/clawchan-satellite.png" width="100%" alt="Satellite Tracking">

### Globe Features
- 🌍 **Earth Sphere** - Realistic planet with atmosphere glow
- 🔄 **OrbitControls** - Drag/rotate with mouse
- ✈️ **Aircraft Markers** - 8+ aircraft with glow effects
- 🛰️ **Satellite Markers** - 6+ satellites with orbit trails
- 📊 **Stats Overlay** - Live tracking counts

---

## 🚨 Crisis Monitoring

<img src="docs/presentations/clawchan-crisis.png" width="100%" alt="Crisis Monitoring">

---

## 🛩️ Aircraft Tracking

<img src="docs/presentations/clawchan-aircraft.png" width="100%" alt="Aircraft Tracking">

---

## 🏗️ Architecture

<img src="docs/presentations/clawchan-architecture.png" width="100%" alt="System Architecture">

### Tech Stack
```
Frontend: React 18 + TypeScript + Vite + Tailwind CSS + Three.js
State: Zustand
Icons: Lucide React
Build: Vite 5
```

### Project Structure
```
📦 World-Monitor-Clawchan-Intelligence
├── 📁 backend/          # API servers & microservices
│   ├── api-gateway/
│   ├── websocket-server/
│   └── data-ingestion/
├── 📁 config/           # Configuration files
├── 📁 docs/             # Documentation
│   └── presentations/   # Visual assets & slides
├── 📁 frontend/         # React frontend application
│   ├── src/
│   │   ├── components/
│   │   │   ├── widgets/     # 11 intelligence widgets
│   │   │   ├── ui/          # shadcn/ui components
│   │   │   └── Globe3D.tsx  # 3D globe component
│   │   ├── store/           # Zustand state management
│   │   ├── api/             # API integrations
│   │   └── hooks/           # Custom React hooks
│   └── public/
├── 📁 infra/            # Infrastructure & deployment
├── 📁 ml/               # Machine learning models
├── 📁 scripts/          # Utility scripts
├── 📁 security/         # Security configurations
└── 📁 tests/            # Test suites
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone repository
git clone https://github.com/blackdragonspear62/World-Monitor-Clawchan-Intelligence.git
cd World-Monitor-Clawchan-Intelligence

# Install dependencies
cd frontend
npm install

# Start development server
npm run dev
```

### Build for Production

```bash
npm run build
```

---

## 📡 Data Sources

| Source | Data Type | API Endpoint |
|--------|-----------|--------------|
| USGS | Earthquakes | `https://earthquake.usgs.gov/fdsnws/event/1/` |
| ADS-B Exchange | Aircraft | `https://api.adsbexchange.com/` |
| N2YO | Satellites | `https://api.n2yo.com/rest/v1/` |
| CoinGecko | Crypto | `https://api.coingecko.com/api/v3/` |
| OpenWeatherMap | Weather | `https://api.openweathermap.org/data/2.5/` |
| The Guardian | News | `https://content.guardianapis.com/` |

---

## 🎨 Visual Design

<img src="docs/presentations/clawchan-closing.png" width="100%" alt="Thank You">

---

## 📝 License

MIT License - See [LICENSE](LICENSE) for details.

---

<div align="center">

**Built with ❤️ by Clawchan Intelligence Agency**

[🌐 Live Demo](https://g5dg7g55gd4ze.ok.kimi.link) • [📊 GitHub](https://github.com/blackdragonspear62/World-Monitor-Clawchan-Intelligence)

</div>
