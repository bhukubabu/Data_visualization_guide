# 🚗 Car Data Visualization & MongoDB Analytics  

## 📌 Project Overview  
This project explores **car data** through **visualization** and **MongoDB analytics**.  
It demonstrates skills in:  
- Data cleaning & visualization (Python, Pandas, Matplotlib)  
- MongoDB for analytics (PyMongo, Aggregation Pipelines)  
- Generating meaningful business insights from raw data  

---

## ⚙️ Tech Stack  
- **Python** (Pandas, Matplotlib, Seaborn)  
- **MongoDB** (Atlas / Local)  
- **PyMongo** (for queries & analytics)  
- **Jupyter Notebook**  

---

## 📂 Project Structure  
```
car-data-analytics/
│
├── car_data_visualization.ipynb   # Notebook with visualizations + MongoDB analytics
├── mongo_connection.py            # MongoDB connection utility
├── car_data.csv                   # Dataset (sample car data)
└── README.md                      # Project documentation
```

---

## 🚀 Getting Started  

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/car-data-analytics.git
cd car-data-analytics
```

### 2️⃣ Install Dependencies
```bash
pip install pandas matplotlib seaborn pymongo jupyter
```

### 3️⃣ Import Data into MongoDB  
Make sure MongoDB is running locally or use MongoDB Atlas.  

```bash
mongoimport --db carDB --collection cars --type csv --headerline --file car_data.csv
```

### 4️⃣ Run Notebook  
```bash
jupyter notebook car_data_visualization.ipynb
```

---

## 📊 MongoDB Analytics Queries  
✔️ **Average Price by Brand**  
✔️ **Cars by Fuel Type**  
✔️ **Top 5 Most Expensive Cars**  
✔️ **Cars with Mileage Above Average**  

Each query result is visualized with charts or tables, followed by **insightful observations**.  

---

## 🔍 Sample Insights  
- **Luxury brands** dominate the higher price segment, while **budget brands** cluster at the lower end.  
- **Petrol cars** dominate the dataset, while **electric vehicles** are still rare.  
- Cars with **above-average mileage** are concentrated in compact & budget-friendly models.  

---
<img width="1497" height="1218" alt="download (2)" src="https://github.com/user-attachments/assets/7fabde51-ea8c-4f95-9aff-8f81fa8d45b0" />

## 🌟 Why This Project?  

This project highlights my ability to:  
- Work with **MongoDB for analytics**  
- Write **complex aggregation queries**  
- Build **data-driven insights & reports**  
- Combine **data engineering & visualization**  

---

## 🔮 Future Improvements  
- Deploy an **interactive Streamlit dashboard** for real-time analytics.  
- Integrate **MongoDB Atlas** for cloud-based analytics.  
- Add **machine learning models** for price/mileage prediction.  
- Extend analysis with **time-series data** (car sales trends).  

---

## 👤 Author  
**[Jaya Bhukta](https://github.com/bhukubabu)**  
📧 bhuktajaya@gmail.com  
