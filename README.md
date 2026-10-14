# 🚖 Uber Dashboard – Power BI

An interactive **Power BI dashboard** that monitors the financial and operational performance of Uber rides. It provides direct statistics and visual charts on bookings, revenue, distance, ratings, and cancellations to support quick, data-driven decisions.

---

## 📸 Screenshots

> Add your screenshots to a `images/` folder and update the paths below.

| Home | Overview |
|------|----------|
| ![Home](images/home.png) | ![Overview](images/overview.png) |

| Rides | Cancelled |
|-------|-----------|
| ![Rides](images/rides.png) | ![Cancelled](images/cancelled.png) |

---

## 🎯 Objective

To showcase detailed sales reports and analyze revenue trends over time, while giving a clear view of ride performance and cancellation behavior across different vehicle types.

---

## 📄 Dashboard Pages

### 1. Home
Landing page with a welcome message and navigation buttons to: **Overview**, **Rides**, and **Cancelled**.

### 2. Overview
- **KPI cards:** Completed Bookings, Lost Bookings, Booking Value, Total Distance, Average Distance
- **Completed Bookings** – area chart by month
- **Booking Value** – bar chart by month
- Toggle between **Month** and **Quarter** views

*Example (Auto vehicle):* 93K completed bookings · 57K lost bookings · $51.8M booking value · 2.51M total distance · 16.75 average distance

### 3. Rides
- Detailed table: Customer ID, Pickup Location, Drop Location, Booking Status (Completed / Incomplete / Cancelled by Customer / Cancelled by Driver) with color coding
- Donut chart comparing **Driver Ratings vs Customer Ratings**
- Interactive **map** with a toggle between **Pickup Location** and **Drop Location**

### 4. Cancelled
- **Cancellation by Vehicle** – cancelled by customer, cancelled by driver, and incomplete rides
- **Cancellation Every Month** – monthly trend (columns + line)
- Donut chart showing the split of cancellations by **Customer (28%)** vs **Driver (72%)**

---

## 🚗 Vehicle Filter

All pages can be filtered by vehicle type using the selector at the bottom of the page:

`Auto` · `Bike` · `Go Mini` · `Go Sedan` · `Premier Sedan` · `eBike` · `Uber XL`

---

## ✨ Key Features

- Clean, modern UI inspired by Uber's branding
- Page navigation with custom buttons and a side menu
- Dynamic filtering by vehicle type
- Month / Quarter drill-down
- Color-coded booking statuses
- Geographic visualization of pickup and drop locations

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – data modeling, DAX measures, and visualization
- **Power Query** – data cleaning and transformation
- **DAX** – KPIs and calculated measures
- **Bing Maps visual** – location analysis

---

## 📊 Key Metrics

| Metric | Description |
|--------|-------------|
| Completed Booking | Total number of successfully completed rides |
| Lost Booking | Rides that were cancelled or not completed |
| Booking Value | Total revenue generated from bookings |
| Total Distance | Sum of ride distances (km) |
| Average Distance | Average distance per ride |
| Driver / Customer Ratings | Sum of ratings given by each side |

---

## 📁 Project Structure

```
├── Uber_Dashboard.pbix     # Power BI report file
├── data/                   # Dataset (CSV)
├── images/                 # Dashboard screenshots
└── README.md
```

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open `Uber_Dashboard.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to the `data/` folder and click **Refresh**.
4. Use the navigation buttons and vehicle filter to explore the report.

---

## 💡 Insights

- Completed bookings fluctuate across the year, with a noticeable dip in February and peaks in March and October.
- Booking value stays fairly stable month to month, with the highest values in January and March.
- Drivers account for the majority of cancellations compared to customers.

---

## 👤 Author

**Thomas Wagdy** — Data Analyst

- GitHub: [ThomasWagdy](https://github.com/ThomasWagdy)
- LinkedIn: [thomas-wagdy](https://www.linkedin.com/in/thomas-wagdy-2355653b3/)

## 📜 License

This project is for educational and portfolio purposes. Uber branding and logos belong to Uber Technologies, Inc.
