# 📱 People Hub Reservation System (PowerApps)

![Project Thumbnail](./assets/thumbnail.png)

---

## 📌 Project Overview
A PowerApps-based Reservation System for JG Summit Olefins Corporation’s recreational facilities. Employees can reserve time slots, submit transport declarations if needed, and receive notifications. Reservations require department head approval, and booked slots are automatically blocked to prevent conflicts, streamlining facility management and ensuring smooth scheduling.

---

## 🖼️ UI Preview
![Project Thumbnail](./assets/desktop_1.png)
![Project Thumbnail](./assets/desktop_2.png)

---

## ⚙️ What’s Under the Hood
This project goes beyond basic PowerApps by applying structured logic and performance optimizations:

- **Data Handling Strategy:**
  - Delegation-aware queries
  - Power Automate Fetching logic to bypass record limits
- **Role-Based Logic:**
  - Conditional rendering based on user roles
  - Secured actions

---

## ✨ Features
- 🔐 Role-based access control  
- ✅ User input validation  
- 🪟 Custom modals  
- 🎨 Minimalist design  
- ⚡ Optimized solution  

---

## 🛠️ Tech Stack
- **PowerApps (Canvas App)**
- **Power Fx**
- **Data Source:** SharePoint (Lists)  
- **Power Automate**

---

## ⚠️ Challenges
- Delegation limits (500–2000 records)  
- Performance issues with large datasets  
- Maintaining clean UX without relying on native components  
- Positioning custom “more options” modals dynamically (attaching them to the correct UI element)

---

## 💡 Solutions Implemented
- Built **custom pagination system**
- Used **delegation-friendly functions** (`Filter`)
- Structured logic to reduce re-renders and heavy computations

---

## 🙌 Special Thanks
- **[powericons.dev](https://www.powericons.dev)** — a great tool for enhancing UI with clean and consistent icons
- **[quickchart.io](https://quickchart.io/)** — a great tool for enhancing UI with easy to use and integrate charts

---

## 📷 Additional Screens
![Project Thumbnail](./assets/desktop_3.png)
![Project Thumbnail](./assets/desktop_4.png)
