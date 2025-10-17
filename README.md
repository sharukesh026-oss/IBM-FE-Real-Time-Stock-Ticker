

# IBM-FE-Real-Time-Stock-Ticker

A modern **React-based frontend application** that displays real-time stock market data for IBM (or any configurable ticker symbol).  
The app streams live prices, charts, and trade updates through WebSocket or REST APIs.

---

## 🚀 Project Overview

**IBM-FE-Real-Time-Stock-Ticker** is designed to show **real-time IBM stock prices** with smooth UI updates and responsive charts.  
It can be easily extended to track multiple stocks or connected to any real-time market data source.

### 🎯 Objectives
- Display real-time stock price and change.
- Render intraday charts for recent price movements.
- Show trade events and timestamps.
- Maintain lightweight, fast, and responsive performance.

---

## 🧩 Features

- ⚡ **Live updates** via WebSocket or REST polling fallback.  
- 📊 **Dynamic charts** (Recharts / Chart.js).  
- 💡 **Configurable ticker symbol** (default: `IBM`).  
- 🌙 **Light/Dark mode toggle**.  
- 🔁 **Auto-reconnect** and error-handling for WebSocket.  
- 🧠 Clean component structure and reusable hooks.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React + Vite |
| Styling | Tailwind CSS |
| Charts | Recharts or Chart.js |
| State Management | React Context / Hooks |
| Data | WebSocket or REST API |
| Testing | Jest + React Testing Library |

---

## ⚙️ Setup and Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/IBM-FE-Real-Time-Stock-Ticker.git
cd IBM-FE-Real-Time-Stock-Ticker
