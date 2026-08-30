# 🏨 Hotel Booking Cancellation & Revenue Analysis

## 📌 Project Overview

This project analyzes **119,000+ hotel booking records** to identify booking patterns, cancellation behavior, pricing trends, and factors associated with hotel cancellations.

The analysis was performed using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

The goal is to understand **why bookings are being cancelled and which factors are associated with higher cancellation rates**, helping hotels improve booking strategies and reduce cancellations.

---

## 🎯 Business Objectives

- Analyze overall hotel booking and cancellation patterns.
- Compare cancellation behavior between City Hotels and Resort Hotels.
- Identify months with higher cancellation rates.
- Analyze Average Daily Rate (ADR) trends.
- Identify countries with the highest number of cancellations.
- Analyze cancellation patterns across different market segments.
- Examine the relationship between booking channels and cancellations.
- Identify potential areas for improving booking and revenue strategies.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data cleaning and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook / Google Colab**

---

## 📊 Dataset

The dataset contains hotel booking information such as:

- Hotel type
- Booking status
- Reservation status
- Reservation status date
- Arrival month
- ADR (Average Daily Rate)
- Country
- Market segment
- Deposit type
- Customer type
- Lead time
- Number of guests
- Previous cancellations

The dataset contains approximately **119,000 booking records**.

---

## 🔍 Analysis Performed

### 1. Hotel-wise Cancellation Analysis

Compared cancellation behavior between:

- Resort Hotel
- City Hotel

City Hotels showed a higher cancellation rate than Resort Hotels.

---

### 2. Monthly Cancellation Rate

Calculated the percentage of bookings cancelled in each month.

The analysis revealed significant variation in cancellation rates across different months.

---

### 3. ADR Analysis

Analyzed **Average Daily Rate (ADR)** across different periods and compared ADR trends between:

- Cancelled bookings
- Non-cancelled bookings
- City Hotels
- Resort Hotels

---

### 4. Market Segment Analysis

Analyzed booking distribution and cancellation behavior across different market segments, including:

- Online Travel Agents
- Offline Travel Agents
- Groups
- Direct
- Corporate
- Complementary
- Aviation

Online Travel Agents represented the largest booking segment and showed a higher cancellation rate than Offline Travel Agents.

---

### 5. Country-wise Cancellation Analysis

Identified the countries contributing the highest number of cancelled bookings.

---

## 📈 Key Insights

- **City Hotels** had a higher cancellation rate (**41.7%**) compared with **Resort Hotels (28.0%)**.
- **Online Travel Agents** had a higher cancellation rate (**46%**) compared with **Offline Travel Agents (23%)**.
- Cancellation rates varied significantly across months.
- Online Travel Agents represented the largest market segment.
- ADR showed noticeable seasonal variation over time.
- Cancellation behavior differs across hotel types, booking channels, and customer segments.

---

## 📊 Visualizations

### ADR: Cancelled vs Non-Cancelled Bookings

![ADR Cancelled vs Non-Cancelled](Images/01_adr_cancelled_vs_non_cancelled.png)

### Cancellation Rate Per Month

![Cancellation Rate Per Month](Images/03_cancellation_rate_per_month.png)

### Bookings by Month and Cancellation Status

![Bookings by Month](Images/04_bookings_by_month_and_status.png)

### Reservation Status by Hotel

![Reservation Status by Hotel](Images/06_reservation_status_by_hotel.png)

---

## 💡 Business Recommendations

Based on the analysis:

- Focus on reducing cancellations from **Online Travel Agent channels**.
- Investigate booking policies that may contribute to high cancellation rates.
- Use historical cancellation patterns to improve demand forecasting.
- Consider targeted cancellation-prevention strategies during high-risk months.
- Analyze deposit and customer-type behavior to identify high-risk bookings.
- Optimize pricing and booking strategies based on seasonal ADR patterns.

---

## 📁 Project Structure

```text
Hotel-booking-analysis/
│
├── Hotel_Booking_Analysis.ipynb
├── README.md
├── requirements.txt
│
└── Images/
    ├── 01_adr_cancelled_vs_non_cancelled.png
    ├── 02_top_10_countries_cancellations.png
    ├── 03_cancellation_rate_per_month.png
    ├── 04_bookings_by_month_and_status.png
    ├── 05_adr_by_hotel.png
    └── 06_reservation_status_by_hotel.png
