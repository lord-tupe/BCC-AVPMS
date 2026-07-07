# BCC AVPMS - Executive Dashboard

A high-fidelity, interactive executive dashboard prototype for the **Blantyre City Council Automated Vehicle Parking Management System (AVPMS)**. This project demonstrates a complete, end-to-end municipal parking workflow—from citizen engagement and mobile money payments to offline field enforcement and executive revenue assurance.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Key Features

### 📱 Citizen & Payment Flows
- **QR Code Initiation:** Simulated camera scanning and bay selection.
- **Mobile Money Integration:** Step-by-step simulation of Airtel Money, TNM Mpamba, and MyCash API requests, PUSH notifications, and webhook callbacks.
- **USSD Fallback:** Interactive terminal simulation for low-bandwidth users.

### 🚓 Enforcement Operations
- **Offline-First Architecture:** Simulated offline ticketing and verification with local queueing and auto-sync.
- **GPS Tracking:** Real-time officer tracking using Leaflet maps.
- **License Plate Verification:** Instant vehicle status and session lookup.

### 📊 Executive & Back-Office Analytics
- **Real-time KPIs:** Monthly revenue, active sessions, system uptime, and citizen satisfaction.
- **Interactive Charts:** Revenue by zone, collection trends, and officer productivity powered by Chart.js.
- **Revenue Heatmap:** Geographic visualization of parking density and revenue using Leaflet.heat.
- **Revenue Assurance:** Automated anomaly detection engine with drill-down audit trails.

### 🎨 UI/UX & Design
- **Modern Dark Theme:** Glassmorphism effects, subtle gradients, and glowing accents.
- **Fully Responsive:** Mobile-first approach with a bottom navigation bar for small screens.
- **Accessible:** ARIA labels, skip links, keyboard navigation, and screen-reader friendly.
- **Smooth Animations:** Intersection Observer for scroll reveals and micro-interactions.

## 🛠️ Tech Stack

- **Core:** Vanilla HTML5, CSS3 (Custom Properties, Grid, Flexbox), ES6+ JavaScript (No frameworks!)
- **Data Visualization:** [Chart.js](https://www.chartjs.org/)
- **Mapping:** [Leaflet.js](https://leafletjs.com/) + [Leaflet.heat](https://github.com/Leaflet/Leaflet.heat)
- **Icons:** [Font Awesome 6](https://fontawesome.com/)
- **Fonts:** Inter & JetBrains Mono (via Fontsource)

## 🚀 Getting Started

Since this is a pure frontend prototype, no build step or server is required.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bcc-avpms-dashboard.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bcc-avpms-dashboard
   ```
3. Open `index.html` in your preferred modern web browser. 
   *(Note: For the best experience with ES6 modules and local storage, it is recommended to serve it via a local server like VS Code Live Server or `python -m http.server`)*.

## 📂 Project Structure

```text
├── index.html        # Main application file (contains HTML, CSS, and JS)
├── README.md         # Project documentation
└── LICENSE           # MIT License
```

## 📝 Future Improvements
- [ ] Integrate with a real backend (Node.js/Express or Python/FastAPI).
- [ ] Connect to actual Mobile Money sandbox APIs (e.g., Africa's Talking).
- [ ] Implement Service Workers for true offline PWA capabilities.
- [ ] Add user authentication and role-based access control (RBAC).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---
*Built with ❤️ for the Blantyre City Council.*
```
