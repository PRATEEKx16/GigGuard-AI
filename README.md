# 🚀 GigGuard AI  
### AI-Based Parametric Insurance for Food Delivery Workers

---

## 🧩 The Problem
Food delivery partners (like Zomato/Swiggy) work in tough and unpredictable conditions.

They often lose income due to:
- 🌧️ Heavy rain or floods  
- 🔥 Extreme heat  
- 🌫️ High pollution  
- ⚠️ App/server downtime  

Currently, they have **no safety net** — if they can’t work, they don’t earn.

---

## 💡 Our Solution
**GigGuard AI** is an AI-powered parametric insurance platform that:
- Monitors real-world conditions (weather, AQI, etc.)  
- Detects income disruption automatically  
- Triggers claims instantly  
- Provides **instant payouts without manual effort**  

---

## 👤 Target Persona
- 🛵 Food delivery workers  
- 💰 Daily/weekly earning dependent  
- 🌍 Outdoor workers  

---

## ⚙️ Key Features

### 🤖 AI Risk Assessment
- Uses weather history and location data  
- Predicts risk levels  
- Dynamically calculates weekly premium  

---

### 🌦️ Parametric Triggers
Automatic payouts when:
- Rainfall > threshold  
- Temperature > threshold  
- AQI > limit  
- App downtime detected  

---

### 🔍 Fraud Detection
- 📍 GPS validation  
- 🚫 Duplicate claim prevention  
- 📊 Activity verification  

---

### ⚡ Instant Payout
- Auto-triggered claims  
- Instant payout via UPI (mock/sandbox)  

---

## 💰 Weekly Premium Model
- ₹20–₹50 per week  

Based on:
- Area risk  
- Worker activity  
- Historical disruptions  

**Example:**
- High-risk (rain-prone area) → ₹50/week  
- Low-risk area → ₹25/week  

---

## 🔄 Workflow
1. 👤 User registers  
2. 🤖 AI calculates premium  
3. 💳 User buys weekly plan  
4. 🌐 System monitors conditions  
5. ⚡ Trigger occurs → auto claim  
6. 💸 Instant payout credited  

---

## 🧠 AI/ML Integration
- 📈 Regression Model → Premium prediction  
- 🧮 Classification Model → Risk level (high/low)  
- 🚨 Anomaly Detection → Fraud detection  

---

## 🏗️ Project Architecture

### 🔷 High-Level Architecture
Frontend (Web App)
↓
Backend Server (Node.js / Express)
↓
AI/ML Engine
↓
Database (MongoDB)
↓
External APIs (Weather, AQI, Platform APIs)
↓
Payment Gateway (Mock / UPI Simulator)


---

### 🔷 System Modules

#### 🖥️ Frontend
- User Registration & Login  
- Dashboard (earnings, coverage)  
- Policy purchase  

---

#### ⚙️ Backend
- User management  
- Policy management  
- Claims processing  

---

#### 🧠 AI Engine
- Risk prediction  
- Premium calculation  
- Fraud detection  

---

#### 🌐 Trigger Engine
- Monitors:
  - Weather API  
  - AQI API  
  - Platform/API downtime (mock)  
- Checks thresholds  
- Automatically triggers claims  

---

#### 💳 Payment Module
- Simulates instant payouts  
- Updates user wallet/balance  

---

## 🔄 Data Flow

User → Registers
↓
Backend → Sends data to AI
↓
AI → Calculates premium
↓
User buys policy
↓
System monitors APIs
↓
Trigger occurs
↓
Claim auto-approved
↓
Payment sent\


---

## 🛠️ Tech Stack

### Frontend
- HTML, CSS, JavaScript (or React)

### Backend
- Node.js / Express  

### Database
- MongoDB  

### APIs
- 🌦️ Weather API (OpenWeather)  
- 🌫️ AQI API  
- 🚦 Traffic/Platform APIs (mock)  
- 💳 Payment Gateway (mock/sandbox)  

---

## 🌐 Platform Choice
👉 **Web Application**  

**Reason:**  
Easy to access, no installation required, and works across all devices.

---

## 🔮 Future Scope
- Expand to other gig workers (Amazon, Zepto, etc.)  
- Integrate real payment systems  
- Advanced AI-based predictive modeling  
- Mobile app version  

---

## 🎯 Our Mission
To provide gig workers with a **financial safety net**, ensuring they don’t lose income due to factors beyond their control.
