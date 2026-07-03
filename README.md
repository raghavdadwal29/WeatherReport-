# 🚀 PULSE – Live Sales Operations Dashboard

A modern **real-time sales dashboard** built with **HTML, CSS, JavaScript, and Chart.js**. It simulates a live e-commerce analytics system by generating synthetic sales data and updating visualizations every few seconds.

![HTML](https://img.shields.io/badge/HTML5-orange)
![CSS](https://img.shields.io/badge/CSS3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

---

## 📌 Overview

PULSE provides a clean, modern interface for monitoring simulated business performance in real time. It demonstrates responsive UI design, dynamic DOM manipulation, data visualization, and client-side data export—all without requiring a backend.

---

## ✨ Features

### 📊 Live KPI Dashboard

* Revenue (Today)
* Total Orders
* Average Order Value (AOV)
* Conversion Rate

### 📈 Interactive Charts

* Real-time Revenue Trend (Line Chart)
* Regional Sales Distribution (Doughnut Chart)
* Sales by Product Category (Bar Chart)
* Order Status Distribution (Doughnut Chart)

### 📋 Live Transaction Table

Displays the latest transactions with:

* Order ID
* Region
* Product Category
* Order Amount
* Order Status
* Timestamp

### 📢 Live Sales Ticker

Continuously scrolling feed of simulated incoming orders.

### ⏰ Real-Time Clock

Displays the current system time with live updates.

### 📤 Export Options

* Export all transaction data as **CSV**
* Export complete dashboard data as **JSON**

### 📱 Responsive Design

Optimized for desktops and tablets using CSS Grid and Flexbox.

---

## 🛠 Technologies Used

| Technology       | Purpose                     |
| ---------------- | --------------------------- |
| HTML5            | Structure                   |
| CSS3             | Styling & Responsive Layout |
| JavaScript (ES6) | Dashboard Logic             |
| Chart.js         | Interactive Charts          |
| Google Fonts     | Modern Typography           |

---

## 📂 Project Structure

```text
PULSE-Dashboard/
│
├── dashboard.html
├── README.md
└── assets/          (optional)
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/pulse-dashboard.git
```

### Open the Project

Simply open **dashboard.html** in any modern web browser.

No installation, build tools, or server setup is required.

---

## 📊 Dashboard Components

### Revenue Stream

A rolling line chart that updates every **2 seconds**, visualizing changes in revenue over time.

### Region Split

Displays live order distribution across:

* North America
* Europe
* Asia Pacific
* Latin America
* Middle East & Africa (MEA)

### Sales by Category

Tracks sales across:

* Electronics
* Apparel
* Home & Garden
* Sports
* Beauty
* Toys
* Books
* Grocery

### Order Status

Visualizes:

* ✅ Fulfilled
* ⏳ Pending
* ❌ Failed

### Transaction Report

Shows the latest customer orders with complete transaction details.

---

## 📁 Export Functionality

Users can download dashboard data directly from the browser.

### CSV Export

Contains:

* Order ID
* Region
* Category
* Amount
* Status
* Timestamp

### JSON Export

Includes:

* Dashboard summary
* Revenue
* Orders
* Conversion rate
* Category statistics
* Region statistics
* Status statistics
* Complete transaction history

---

## ⚙️ Data Simulation

The dashboard generates **synthetic e-commerce sales data** on the client side.

Every **2 seconds** it automatically:

* Creates new transactions
* Updates revenue
* Updates order counts
* Refreshes all charts
* Refreshes the transaction table
* Updates KPI cards

No backend or database is required.

---

## 🎨 UI Highlights

* Modern dark theme
* Animated LIVE status indicator
* Smooth chart animations
* Responsive layout
* Gradient branding
* Custom typography
* Professional analytics dashboard design

---

## 🔮 Future Improvements

* User authentication
* Backend integration
* Database support
* WebSocket live updates
* Date range filtering
* Search & filtering
* Theme switcher (Dark/Light)
* PDF report generation
* User management
* Real sales API integration

---

## 📸 Screenshot

> Add a screenshot of the dashboard here for a better GitHub presentation.

Example:

```text
screenshots/dashboard.png
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Developed as a front-end dashboard project to demonstrate real-time data visualization using HTML, CSS, JavaScript, and Chart.js.

⭐ If you found this project useful, consider giving it a star on GitHub!
