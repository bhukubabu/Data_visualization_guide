# 🚗 Car Data Analysis – From Raw Data to Actionable Insights

## 🌟 Why This Project Matters

In a **fast-paced, high-ownership environment**, data isn’t just numbers — it’s the compass guiding product, growth, and user experience.
This project transforms raw used car data from [CarDekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho) into **clear, actionable insights** using **SQL** for analysis and visual storytelling for decision-making.

Just like a growth/product intern role, the challenge here was:

* **Own the problem** → Clean and structure raw data.
* **Ask the right questions** → Which features impact price the most? How does seller type vary across fuel types?
* **Deliver insights quickly** → SQL queries that can directly feed into dashboards.
* **Communicate findings thoughtfully** → Present charts and summaries that empower decisions.

---

## 📌 My Role

* **End-to-End Ownership**: Took full responsibility for data extraction, cleaning, analysis, and presentation.
* **Analytical Thinking**: Broke down the dataset into smaller questions around trends, distributions, and correlations.
* **Cross-Functional Mindset**: Structured outputs so that product, marketing, and operations teams could all derive insights.
* **AI-First Approach**: Used ChatGPT to speed up query drafting and validate complex aggregations.

---

## 🎯 Project Highlights

1. **Price Trends & Market Patterns**

   * Identified year-wise depreciation trends in selling prices.
   * Found how transmission and fuel type shift market value.
2. **User Segmentation**

   * Mapped owner category distribution to understand market composition.
   * Segmented sellers by type and correlated with fuel choice.
3. **Performance Specs Impact**

   * Compared engine capacity, mileage, and power with selling prices to find high-value car types.
4. **High-Value Vehicles**

   * Ranked the **Top 20 cars** by selling price for premium market targeting.

---

## 📂 Dataset

**Records:** \~7,900
**Fields:** Name, Year, Selling Price, Kilometers Driven, Fuel Type, Seller Type, Transmission, Owner, Mileage, Engine, Max Power, Torque, Seats.

---

## 🛠 Tech Stack

* **SQL** – MySQL-compatible queries for cleaning, aggregation, and ranking.
* **Python (optional)** – For plotting charts from SQL outputs.
* **Matplotlib / Seaborn** – Visualization.
* *(Bonus Alignment to JD)* This could be adapted to **PostHog** or **Retool** dashboards to make data live and actionable.

---

## 📊 Key Insights & Visuals

> *(Below images will be added in `images/` folder)*

### 1️⃣ Selling Price vs Year

![Price vs Year](images/download%(1).png)
Shows depreciation patterns and peaks for specific years.

### 2️⃣ Price by Fuel & Transmission

![Fuel Price](images/price_by_fuel.png) | ![Transmission Price](images/price_by_transmission.png)

### 3️⃣ Owner Segmentation

![Owner Pie Chart](images/owner_distribution.png)
Highlights % split between first, second, and third owners.

### 4️⃣ Seller vs Fuel Insights

![Seller Type by Fuel](images/seller_type_by_fuel.png)
Guides targeting for dealer campaigns.

### 5️⃣ Performance Specs vs Price

![Mileage vs Price](images/mileage_vs_price.png)
![Engine vs Price](images/engine_vs_price.png)

### 6️⃣ Top 10 Cars by Price

![Top Cars Chart](images/top_10_cars.png)

---

## 📈 Skills Demonstrated (Matching the Role)

* **SQL Mastery** – Wrote optimized queries for trend, segmentation, and ranking analysis.
* **Actionable Analysis** – Focused on metrics that could drive business decisions.
* **Ownership** – Managed entire pipeline from CSV → SQL DB → Visual Insights.
* **Clear Communication** – Visuals and summaries make data easy for any stakeholder to act on.
* **AI-First Workflow** – Used AI tools to accelerate query building and validation.
* **Cross-Functional Thinking** – Structured outputs for potential integration into PostHog, Retool, or Mixpanel.

---

## 🚀 How to Run

1. **Import the Dataset**

   ```sql
   LOAD DATA INFILE '/path/to/Car details v3.csv' ...
   ```
2. **Run the Analysis Script**

   ```bash
   mysql -u username -p database_name < car_details_analysis.sql
   ```
3. **Export Results & Visualize**

   * Use Python, Excel, or BI tools to turn outputs into visuals.

---

## 💡 How This Connects to the Role

* **Build Dashboards** → These SQL queries can directly feed PostHog or Retool for real-time analysis.
* **Analyse Funnels & Campaigns** → Similar aggregation logic applies to user journey data.
* **Improve Retention & Conversion** → Insights structure supports metric monitoring.
* **Communicate Effectively** → Charts and summaries make complex data accessible to all teams.

---

