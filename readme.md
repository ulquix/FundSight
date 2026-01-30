# 🚀 **FundSight** – Your Gateway to Smarter Investment Decisions  

FundSight is a cutting-edge **web-based analytics platform** designed for investors, venture capitalists, and entrepreneurs who want to make **data-driven investment decisions**. It enables users to **analyze and visualize startup funding trends** through intuitive charts and graphs, providing insights based on:  

✅ **Sectors** – Understand which industries are thriving.  
✅ **Performance** – Identify high-growth startups.  
✅ **Total Funding** – Track capital inflow in the startup ecosystem.  
✅ **Region** – Discover geographical funding trends.  
✅ **Year** – Analyze historical funding patterns.  

## 🌟 **Key Features**  

🔹 **Explore Pre-Stored Data** – Get instant insights from our curated startup funding database.  
🔹 **Analyze Your Own Data** – Upload datasets and create **custom workflows** for tailored analysis.  
🔹 **Interactive Data Visualization** – Dynamic graphs and charts make analysis effortless.  
🔹 **Fast & Efficient** – Built with **Vite + React** for a seamless experience.  

---

## 🛠 **Tech Stack**  
FundSight is built using modern web technologies to ensure **speed, scalability, and performance**:  

- **Frontend:** ⚡ Vite + React (Fast and reactive UI)  
- **Backend:** 🖥️ Node.js (Robust and scalable API handling)  

---

## 🚀 **Getting Started**  

### **Prerequisites**  
Before you begin, ensure you have the following installed:  
- [Node.js](https://nodejs.org/) (Latest LTS recommended)  
- npm or yarn (for package management)  

### **Installation**  

1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/princeyadavv/FundSight.git
   cd FundSight
   ```

2️⃣ Install all dependencies (monorepo setup):  
   ```bash
   npm install
   ```

   This will install dependencies for both the frontend and backend workspaces automatically.

---

## ▶️ **Running the Application**  

### **Using Monorepo Commands (Recommended)**

🚀 **Run both Frontend & Backend in development mode:**  
```bash
npm run dev
```

🎯 **Run only the Backend:**  
```bash
npm run dev:backend
```

🎯 **Run only the Frontend:**  
```bash
npm run dev:frontend
```

### **Alternative: Running Individually**

💡 **Start the Backend:**  
```bash
cd backend
npm run dev
```

💡 **Start the Frontend:**  
```bash
cd Frontend
npm run dev
```

Once both services are running, visit **`http://localhost:5173/`** (or the port Vite provides) to explore FundSight!  

---

## 🏗️ **Monorepo Structure**

This project uses **npm workspaces** for efficient monorepo management:

```
fundsight/
├── package.json          # Root package with workspace configuration
├── backend/              # Backend API (@fundsight/backend)
│   ├── package.json
│   ├── server.js
│   └── ...
├── Frontend/             # Frontend app (@fundsight/frontend)
│   ├── package.json
│   ├── vite.config.js
│   └── ...
└── node_modules/         # Shared dependencies
```

### **Benefits:**
- ✅ Single `npm install` for all packages
- ✅ Shared dependencies across workspace
- ✅ Centralized scripts management
- ✅ Easier dependency version management

---

## 🤝 **Contributing**  
We welcome contributions! 🚀 If you’d like to enhance FundSight, follow these steps:  

1. **Fork** the repository.  
2. Create a **new branch** (`feature/awesome-feature`).  
3. **Commit** your changes.  
4. Submit a **Pull Request**.  

Your contributions help make FundSight better for everyone!  

---

## 📜 **License**  
This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.  

---

🚀 **Start analyzing startup trends today with FundSight!**  
