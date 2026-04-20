# CYBERJOAR Strategic Intelligence Fusion Dashboard

```text
 ██████╗██╗   ██╗██████╗ ███████╗██████╗      ██╗ ██████╗  █████╗ ██████╗
██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗     ██║██╔═══██╗██╔══██╗██╔══██╗
██║      ╚████╔╝ ██████╔╝█████╗  ██████╔╝     ██║██║   ██║███████║██████╔╝
██║       ╚██╔╝  ██╔══██╗██╔══╝  ██╔══██╗██   ██║██║   ██║██╔══██║██╔══██╗
╚██████╗   ██║   ██████╔╝███████╗██║  ██║╚█████╔╝╚██████╔╝██║  ██║██║  ██║
 ╚═════╝   ╚═╝   ╚═════╝ ╚══════╝╚═╝  ╚═╝ ╚════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```

![Built With JavaScript](https://img.shields.io/badge/Built%20With-JavaScript-f7df1e?logo=javascript&logoColor=000)
![Powered by Claude AI](https://img.shields.io/badge/Powered%20by-Claude%20AI-7b61ff)
![Leaflet Maps](https://img.shields.io/badge/Leaflet-Maps-199900?logo=leaflet&logoColor=fff)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=fff)
![License MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## 🎯 Project Overview

CYBERJOAR Dashboard is a tactical intelligence visualization and analysis interface designed to fuse multiple data sources into one operational picture.

Problem Statement PS1 focused on intelligence fusion, geospatial situational awareness, and rapid analyst workflows under high-pressure conditions.

**Military-grade intelligence fusion platform**

## ✨ Features

- 🗺️ **Real-time Geospatial Map** (Leaflet.js + Terrain/Satellite toggle)
- 🔵 **Multi-source Intel Nodes** (OSINT/HUMINT/IMINT color-coded)
- 📁 **Drag & Drop File Ingestion** (CSV/JSON/Excel/JPG)
- ☁️ **MongoDB Atlas Cloud Sync**
- 🤖 **Claude AI Powered OSINT Report Generator**
- 📡 **Live Intel Feed** with auto-updates
- 🎯 **Hover & Click popups** with image preview
- ⌨️ **Keyboard Shortcuts**
- 📄 **SITREP Export**
- 🛰️ **Radar Widget**

## 🖥️ Screenshots

<!-- Add screenshots here -->

## 🚀 Quick Start

### Frontend

Simply open `index.html` in browser.

### Backend

```bash
cd backend
npm install
# Add MongoDB URI to .env
npm start
```

## 📁 Project Structure

```text
cyberjoar-dashboard/
├── index.html          # Main dashboard (frontend)
└── backend/
    ├── server.js       # Express + MongoDB + S3 API
    ├── package.json
    └── .env            # Environment variables
```

## 🔧 Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML/CSS/JS | Frontend Dashboard |
| Leaflet.js | Interactive Maps |
| MongoDB Atlas | Cloud Database |
| Node.js + Express | Backend API |
| AWS S3 | Image Storage |
| Claude AI API | Intelligence Reports |
| SheetJS | Excel Processing |

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| R | Recenter Map |
| S | Focus Search |
| G | Toggle AI Panel |
| 1/2/3/4 | Filter Sources |
| ESC | Close Panels |
| ? | Show Shortcuts |
| Ctrl+Shift+D | Debug Audit |

## 🎮 How to Use

1. Open the dashboard (`index.html`) and verify the map + feed are active.
2. Upload intelligence files:
   - CSV/JSON for structured OSINT/HUMINT node ingestion
   - JPG for IMINT image placement and preview
3. Use **☁️ CLOUD INTEL SOURCES** panel:
   - Check MongoDB connectivity status
   - Click **⟳ SYNC FROM MONGODB** to load cloud nodes
   - Click **SEED DATABASE** to insert sample nodes, then auto-sync
4. Generate AI report:
   - Enter API key in AI panel
   - Choose analysis type and optional mission context
   - Click **GENERATE REPORT**
5. Export SITREP from the footer button to produce a mission snapshot report.

## 📊 Problem Statement Coverage

| Requirement | Status |
|------------|--------|
| OSINT Data Ingestion | ✅ Implemented |
| HUMINT Manual Upload | ✅ Implemented |
| IMINT Image Upload | ✅ Implemented |
| MongoDB Integration | ✅ Implemented |
| AWS S3 Support | ✅ Mock Ready |
| Geospatial Map | ✅ Implemented |
| Hover Popups | ✅ Implemented |
| Interactive Markers | ✅ Implemented |
| AI Analysis | ✅ Implemented |

## 🔐 Environment Variables

```env
PORT=3000
MONGODB_URI=mongodb+srv://...
AWS_ACCESS_KEY_ID=...
AWS_SECRET_ACCESS_KEY=...
AWS_REGION=ap-south-1
S3_BUCKET_NAME=...
```

## 👨‍💻 Developer Note

Built as part of CYBERJOAR AI hiring assignment OC.41335.2026.59218

## 📜 License

MIT
