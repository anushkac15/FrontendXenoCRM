# 🎯 AI-Powered Campaign Management Interface – Frontend

A dynamic, responsive, and testable frontend interface for campaign and customer management, built with React.js. Designed with performance, accessibility, and modularity in mind, the interface supports real-time statistics, AI-driven insights, and intuitive user interactions.

### 🔗 **Live Demo**: [Visit the Deployed App »](https://anushkacrm.netlify.app/login)


## 🌟 Features

* **Interactive Dashboard** with real-time campaign insights
* **Drag-and-Drop Rule Builder** for custom campaign logic
* **Customer Management** with advanced search and filters
* **Campaign History** tracking with visual stats and logs
* **Responsive UI** with **Dark/Light Mode** support
* **Tooltips, Modals, Charts**, and smooth animations
* Built with a **quality-first approach** for scalability and testability


## 🛠️ Tech Stack

* **React.js** with functional components and hooks
* **Material-UI (MUI)** for consistent, customizable styling
* **Redux Toolkit + RTK Query** for scalable state & API management
* **React Router** for client-side navigation
* **Axios** for API interactions
* **Chart.js** for real-time data visualization


## 🚦 Quick Start

```bash
# Install dependencies
cd frontend
npm install

# Environment setup
cp .env.example .env
# Update environment variables:
REACT_APP_API_URL=http://localhost:5000
REACT_APP_WS_URL=ws://localhost:5000

# Run development server
npm start
```


## 📁 Project Structure

```
frontend/
├── public/          # Static files
├── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Page-level components
│   ├── redux/       # State management logic
│   ├── services/    # API service handlers
│   ├── utils/       # Helper functions
│   ├── hooks/       # Custom React hooks
│   └── styles/      # Global theme & styling
└── package.json
```


## 🔍 Key Components

### Dashboard

* Real-time campaign stats
* AI-powered insights
* Interactive charts & analytics

### Campaign Management

* Campaign creation form
* Drag-and-drop rule builder
* Template editor & audience preview

### Customer Management

* Filterable customer list
* Customer detail view
* Order and engagement history


## 🎨 UI Elements

* **Buttons**, **Cards**, **Tables**, **Modals**, **Tooltips**
* **StatsCard** for animated KPIs
* **InsightCard** for AI insights
* **ProgressBar** for campaign tracking
* **Charts** for live data feedback


## 🧪 Testing & Quality

* Designed with **testability** in mind
* API endpoints tested using **Postman**
* Compatible with tools like **Appium**, **REST Assured**, and **Playwright**
* Structured for easy integration with **CI/CD pipelines**
* Focus on identifying **edge cases**, graceful error handling, and **debugging support**


## 🚀 Building for Production

```bash
# Create production build
npm run build

# Test production build locally
npm run serve
```


## 📱 Responsive & Accessible

* Mobile-first design
* Cross-device compatibility
* Responsive tables and charts
* Touch-friendly components
* Keyboard & screen reader accessibility


## ⚡ Performance Optimizations

* Code splitting & lazy loading
* Memoization for UI rendering
* Lightweight bundle generation
* Optimized image loading


## 🤝 Contribution Guide

1. Fork the repository
2. Create a feature branch
3. Commit your changes with clear messages
4. Push and open a Pull Request
