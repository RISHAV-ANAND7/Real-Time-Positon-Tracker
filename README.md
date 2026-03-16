# Real-Time Position Tracker

**Real-Time Position Tracker — Track locations instantly with live updates. 🌍📍**

Real-Time Position Tracker is a web application that allows multiple users to share and track live locations on a map in real time. It uses WebSockets to send location updates instantly between clients and the server, providing a smooth and interactive experience.

---

## ✨ Live Demo

Coming Soon 🚀

---

## 🧭 Overview

Real-Time Position Tracker demonstrates how modern web applications can track and update user locations instantly using real-time communication.

When a user opens the application, the browser captures their location and sends it to the server. The server then broadcasts the location to all connected users, allowing everyone to see live position updates on the map.

This type of system is similar to how live tracking works in apps like ride-sharing or delivery tracking.

---

## ✨ Features

🔹 **Real-Time Location Tracking** – Share and update locations instantly.
🔹 **WebSocket Communication** – Fast updates using Socket.IO.
🔹 **Live Map Updates** – View positions on a dynamic map interface.
🔹 **Multiple User Tracking** – Track locations of all connected users.
🔹 **Lightweight & Fast** – Simple architecture for smooth performance.
🔹 **Open Source** – Easy to modify, extend, and learn from.

---

## ⚙️ Tech Stack

| Layer                   | Technology            |
| ----------------------- | --------------------- |
| Backend                 | Node.js               |
| Framework               | Express.js            |
| Real-Time Communication | Socket.IO             |
| Frontend                | HTML, CSS, JavaScript |
| Maps                    | Leaflet.js            |
| Runtime                 | Node.js               |

---

## 🏁 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js (v16 or higher)
* npm
* Git

---

### Installation & Setup

Clone the repository:

```
git clone https://github.com/RISHAV-ANAND7/Real-Time-Positon-Tracker.git
```

Navigate to the project directory:

```
cd REALTIME_TRACKER
```

Install dependencies:

```
npm install
```

Start the server:

```
node app.js
```

Open your browser and visit:

```
http://localhost:3000
```

You should now see the live location tracker running locally.

---

## 📜 Project Structure

```
Real-Time-Positon-Tracker
│
├── public
│   ├── css
│   ├── js
│
├── views
│   └── index.ejs
│
├── app.js
├── package.json
└── README.md
```

---

## 🧠 How It Works

1. User opens the web application.
2. Browser asks for **location permission**.
3. The browser captures location using the **Geolocation API**.
4. Location coordinates are sent to the server using **Socket.IO**.
5. The server broadcasts the location to all connected users.
6. The map updates in real time with the latest positions.

---

## 🚀 Future Improvements

* User authentication
* Unique markers for different users
* Route tracking (travel history)
* Mobile-friendly UI
* Room-based tracking (private groups)

---

## 🤝 Contributing

Contributions are always welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

**Rishav Anand**
GitHub: https://github.com/RISHAV-ANAND7

Project Link:
https://github.com/RISHAV-ANAND7/Real-Time-Positon-Tracker
