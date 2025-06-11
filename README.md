# ⚡ EVolve_DBMS

**EVolve_DBMS** is an Electric Vehicle (EV) charging session management system developed using **Java Swing for the GUI** and **SQL** for the backend database. It allows both **Admin** and **User** roles to efficiently manage and book charging sessions.

---

## 🛠️ Tech Stack

- **Frontend:** Java Swing
- **Backend:** MySQL / SQLite (SQL-based DBMS)
- **Language:** Java

---

## 👤 User Features

- 🔍 **Search Charging Stations** by city
- 📅 **Book a Charging Session**
- 💼 **View Wallet Balance**
- 📜 **See Previous Bookings**
- ⏳ **Upcoming Sessions** with options to:
  - Cancel session
  - Mark session as complete
- ✍️ **Give Feedback**
- 📚 **Help Desk**:
  - Unit rates & estimated charging time
  - Reward categories and counts

---

## 🛡 Admin Features

- ➕ **Add Charging Station**
- 📝 **Update Charging Station Info**
- ❌ **Remove Charging Station**
- 📍 **View All Charging Stations**
- 👛 **Check User Wallets**
- 💸 **View Transactions**
- 💬 **Read Feedbacks**

---

## 📐 Calculations Used

- **Cost of Session:**  
  `Cost = rate × number of units`

- **Estimated Time Required:**  
  `Time = 3 × number of units`  
  *(in minutes; added to starting time for scheduling)*


