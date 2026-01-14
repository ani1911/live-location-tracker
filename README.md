# 🌍 Live Location Tracker

A real-time device location tracking web application built using **Node.js**, **Express**, **Socket.IO**, **Leaflet.js**, and **EJS**.  
The application displays live device movements on an interactive map with instant updates across all connected clients.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b28331cc-f354-4e1b-ad15-6e8fae2a86ed" alt="Live Location Tracker Map">
</p>

---

## 🚀 Features

- 📍 Real-time device location tracking
- 🗺️ Interactive maps using Leaflet
- 🔄 Live updates via Socket.IO (WebSockets)
- 🧩 Server-side rendering with EJS templates
- 👥 Supports multiple connected clients
- 🌐 Uses Browser Geolocation API
- 📱 Responsive and mobile-friendly

---

## 🧠 How It Works

1. Client connects to the backend using **Socket.IO**
2. Browser fetches live GPS coordinates
3. Coordinates are sent to the server in real time
4. Server broadcasts updates to all connected clients
5. Leaflet updates markers instantly on the map

---

## 🛠️ Tech Stack

- **Templating Engine:** EJS
- **Backend:** Node.js, Express.js
- **Real-Time:** Socket.IO
- **Maps:** Leaflet.js with OpenStreetMap tiles
- **Geolocation:** Browser Geolocation API

---

You can build on top of this project to create:

🚚 Fleet & logistics tracking

🧭 Geofencing applications

🕒 Location history & playback

🔐 Auth-based user tracking

🗄️ Database-backed tracking systems
