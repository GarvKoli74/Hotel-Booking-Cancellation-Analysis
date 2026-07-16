# Hotel Booking Cancellation Analysis (Excel)

## 📌 Project Overview & Objectives
This project focuses on analyzing historical hotel booking data to decode customer cancellation behavior, seasonal demand variations, and key operational risk factors[cite: 2]. By leveraging advanced Excel and dynamic data modeling, the objective was to provide actionable insights to help hotels reduce churn, optimize room pricing, and stabilize revenue forecasting[cite: 2].

The analysis explicitly targets:
* The impact of lead times, market segments, and room types on cancellation probability[cite: 2].
* Seasonal fluctuations in booking volumes and cancellations[cite: 2].
* Building an interactive executive dashboard for stakeholder exploratory analysis[cite: 2].

---

## 🛠️ Tools & Data Preprocessing
* **Core Stack:** Advanced MS Excel (Pivot Tables, Pivot Charts, Custom Slicers, and Timelines)[cite: 2].
* **Data Cleaning & Engineering:** 
  * Deduped dataset and standardized categorical fields (Guest, Hotel, and Meal types)[cite: 2].
  * Engineered time-dimension features (Year, Month, Week) from raw booking dates[cite: 2].
  * Built boolean flags (`Is_Cancelled`) and aggregate fields (`Total Nights`) to streamline analytical querying[cite: 2].

---

## 📊 Key Analytical Insights & Business Value
* **Lead Time Uncertainty:** Bookings with longer lead times (early reservations) displayed a significantly higher cancellation rate, signaling volatile travel plans[cite: 2].
* **Segment Risk & Acquisition Channels:** "Transient" guests and bookings generated via Online Travel Agents (OTAs) accounted for the absolute highest cancellation volumes[cite: 2]. Conversely, "Group" bookings and family segments proved highly stable[cite: 2].
* **Commitment Signals:** A strong negative correlation was found between custom requests and cancellations—guests who submitted more special requests had a drastically lower likelihood of canceling, indicating higher commitment[cite: 2].
* **Seasonality & Property Dynamics:** Cancellation volumes peaked during summer and December due to high flexible travel demand[cite: 2]. City Hotels experienced higher overall volume but suffered worse cancellation rates than Resort Hotels[cite: 2].

---

## 🖥️ Executive Dashboard Features
The final interactive dashboard acts as a central hub for hotel operations, displaying:
* **High-Level KPIs:** Total Bookings, Total Cancellations, Overall Cancellation Rate, Peak Months, and Most Active Guest Type[cite: 2].
* **Visual Breakdown Modules:** Monthly Trend Charts, Guest Type Comparisons (Confirmed vs. Cancelled), Location-Based Risk Analysis, and Lead Time Distribution charts[cite: 2].
* **Multi-Select Dynamic Slicers:** Allows instant data filtering by **Guest Type**, **Arrival Year**, **Meal Type**, **Hotel Type**, and **Market Segment**[cite: 2].

---

## 🖼️ Dashboard Preview
*(Take a screenshot of your Excel dashboard, upload the image file to this repository, and paste the image link here to display it visually to recruiters!)*
