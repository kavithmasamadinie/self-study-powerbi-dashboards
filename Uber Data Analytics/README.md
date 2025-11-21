# Uber Ride Analysis Project

This project contains a Power BI dashboard (`Uber.pbix`) and a dataset (`ncr_ride_bookings.csv`) used to analyze Uber rides in the NCR region. The analysis includes booking patterns, ride completion rates, customer and driver behavior, and operational metrics such as wait time, completion time, cancellations, and ride values.

## 📁 Project Structure

```
├── Uber.pbix                 # Power BI dashboard/report
├── ncr_ride_bookings.csv     # Dataset containing Uber ride booking details
└── README.md                 # Project documentation (this file)
```

## 📊 Dashboard Overview

The **Power BI Dashboard** includes insights such as:

* Total bookings, completed rides, incomplete rides, and cancellations
* Customer and driver cancellation patterns
* Ride distances and booking values
* Vehicle type distribution
* Average VTAT (Vehicle Turnaround Time) and CTAT (Customer Turnaround Time)
* Peak time and location-based analytics

## 🧵 Dataset Description

The dataset (`ncr_ride_bookings.csv`) includes the following key columns:

* **Date, Time** – Ride booking timestamps
* **Booking ID, Customer ID** – Unique identifiers
* **Booking Status** – Completed, Incomplete, or No Driver Found
* **Vehicle Type** – eBike, Auto, Bike, Premier Sedan, Go Sedan
* **Pickup & Drop Locations** – Source and destination points
* **Avg VTAT / Avg CTAT** – Average operational metrics
* **Cancelled / Incomplete Ride Info** – Reasons and counts
* **Booking Value** – Total value of the ride
* **Ride Distance** – Distance traveled
* **Driver & Customer Rating** – Ratings after the ride
* **Payment Method** – Cash, UPI, Card, etc.

## 🚀 How to Use This Project

### 1. **Explore the Power BI Dashboard**

Open the `Uber.pbix` file in Power BI Desktop to view complete analytics.

### 2. **Work With the Dataset**

You can load the CSV into any data analytics tool:

* Python (Pandas)
* Power BI
* Excel
* SQL

Example (Python):

```python
import pandas as pd

df = pd.read_csv('ncr_ride_bookings.csv')
print(df.head())
```

## 📈 Key Insights You Can Derive

* Performance of different vehicle categories
* User behavior based on ratings
* Impact of location on ride availability
* Financial analysis from booking values
* Peak hour trends and heatmaps
* Cancellation trends and operational bottlenecks

## 🏗️ Future Improvements

* Add predictive modeling (ride cancellation prediction)
* Customer segmentation using clustering
* Route optimization analytics
* Deployment of interactive dashboard on web

## 📬 Contact

If you have questions or improvements, feel free to open an issue or submit a pull request.

---

This project aims to provide actionable insights into the ride-hailing ecosystem using real-world‑style datasets and BI tools.
