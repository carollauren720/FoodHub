
# 🌉 **FoodBridge**

> _Food Donation Made Simple_  
> **Connecting restaurants with NGOs to reduce food waste and fight hunger through AI-powered smart matching.**

---

## 🎯 **Problem Statement**

🌍 **40%** of food produced globally is wasted  
🍽️ **828 million** people face hunger worldwide  
💸 **$1 trillion** lost annually due to food waste  

**FoodBridge** solves this by creating a **seamless digital bridge** between **restaurants** with surplus food and **NGOs** serving communities in need.

---


---


---


---

## ✨ **Key Features**

### 🍽️ For Restaurants
- **Smart Food Listing** — Upload food photos; AI recognizes type & quantity  
- **Donation Dashboard** — Track all donations and impact metrics  
- **Real-Time Status** — See when donations are claimed  
- **Impact Tracking** — View kg saved, meals donated, and your impact score


### 🤝 For NGOs
- **Food Discovery** — Browse donations via interactive map  
- **Smart Recommendations** — AI suggests relevant donations  
- **One-Click Claiming** — Schedule pickups easily  
- **Direct Contact** — Connect directly with restaurants


### 👨‍💼 For Admins
- **User Management** — Verify and manage restaurants/NGOs  
- **Analytics Dashboard** — View real-time statistics & insights  
- **Activity Monitoring** — Track all platform activity  
- **Donation Oversight** — Manage all donations across the system  


## 🌱 **Acknowledgments**

Inspired by the **United Nations Sustainable Development Goals**:  
- 🥗 **SDG 2:** Zero Hunger  
- 🔁 **SDG 12:** Responsible Consumption and Production  

📊 Food waste statistics sourced from **FAO**  
💡 Inspired by food rescue initiatives worldwide  

---

## 🔮 **Future Scope**

FoodBridge aims to grow with new innovations and impact-driven features.  
Here are some of the planned enhancements for future releases:

### 💡 Upcoming Features
- 🍱 **AI-Powered Food Estimator** — Predict how much food to prepare based on past data on food production and wastage.  
- 💖 **Donation Page for Crowdfunding** — A community-driven page to fund food rescue efforts through easy form submissions.  
- 🎂 **Share Your Birthday Initiative** — Users can celebrate their birthday by donating meals to children in partnership with NGOs.  
- 🔐 **Forgot / Reset Password** — Secure account recovery option for users.  
- 🖼️ **Profile Picture Management** — Upload and update profile photos for restaurants and NGOs.  
- 🍛 **Partial Food Ordering for NGOs** — NGOs can claim a portion of available food instead of full donations.  
- 🔔 **Real-Time Notifications** — Instant alerts for restaurants and NGOs when donations are posted or claimed.

---

## 🏗️ **Tech Stack**

### 🔧 Backend
- **Node.js + Express.js** — RESTful API  
- **PostgreSQL** — Relational Database  
- **JWT** — Authentication  
- **Bcrypt** — Password Hashing  
- **Multer** — File Upload Handling  

### 💻 Frontend
- **React.js** — UI Framework  
- **React Router** — Routing & Navigation  
- **Axios** — HTTP Client  
- **Leaflet** — Interactive Maps  
- **CSS3** — Styling  

### ⚙️ DevOps
- **Git** — Version Control  
- **GitHub** — Repository Hosting  

---

## 🚀 **Quick Start Guide**

### ✅ Prerequisites
- Node.js (v18+)  
- PostgreSQL (v14+)  
- Git

---

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/foodbridge.git
cd foodbridge
````

### 2️⃣ Setup Backend

```bash
cd backend
npm install
cp .env.example .env
```

Edit `.env` with your database credentials, then:

```bash
mkdir uploads
```

### 3️⃣ Setup Database

```bash
psql -U postgres
CREATE DATABASE foodbridge;
\c foodbridge
\i models/schema.sql
\q
```

### 4️⃣ Start Backend

```bash
npm run dev
```

Server runs on 👉 **[http://localhost:5000](http://localhost:5000)**

### 5️⃣ Setup Frontend (Optional)

```bash
cd ../frontend
npm install
npm start
```

App runs on 👉 **[http://localhost:3000](http://localhost:3000)**

---

## 🧪 **Quick Test**

Check if API is running:

```bash
curl http://localhost:5000/api/health
```

Expected response:

```json
{"status": "OK", "message": "FoodBridge API is running"}
```

---

## 🔐 **Default Test Accounts**

| Role          | Email                                               | Password |
| ------------- | --------------------------------------------------- | -------- |
| 👑 Admin      | [admin@foodbridge.com](mailto:admin@foodbridge.com) | admin123 |
| 🍴 Restaurant | [restaurant@test.com](mailto:restaurant@test.com)   | admin123 |
| ❤️ NGO        | [NGOngo@test.com](mailto:NGOngo@test.com)           | admin123 |

---

## 📜 **License**

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 💖 **Made with Love**

> *“Small acts, when multiplied by millions of people, can transform the world.”* 🌍
> Made with ❤️ for a **better, hunger-free world**.

---

