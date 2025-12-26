# 🚍 City Public Transport Ridership Analysis
### Exploratory Data Analysis (EDA) + Route Popularity Detection with Interactive Frontend

---

## 📌 Project Overview

This project is developed as part of my **AI/ML Minor – Exploratory Data Analysis (EDA)** coursework.  
The aim of this project is to analyze **city public transport ridership data**, identify popular routes, and visualize passenger trends.  

As an extension, I integrated an **interactive frontend** that allows users to input data and instantly view updated route popularity using live charts.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on ridership data  
- Analyze passenger distribution and daily trends  
- Detect popular transport routes based on passenger count  
- Visualize results using bar charts and line graphs  
- Build an interactive frontend for real-time input and output  

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Gradio** – Frontend integration
- **Google Colab** – Development environment

---

## 📊 Dataset Description

A **synthetic dataset** is generated to simulate real-world city transport data.

### Dataset Features:
| Column Name | Description |
|------------|------------|
| Date | Travel date |
| Route | Route ID (R1 – R5) |
| Transport_Type | Bus, Metro, Tram |
| Passengers | Number of passengers |

Synthetic data ensures the project is self-contained and easy to reproduce.

---

## 🔍 Exploratory Data Analysis (EDA)

The following EDA steps are performed:

- Dataset inspection using `info()` and `describe()`
- Passenger distribution analysis
- Daily ridership trend analysis
- Route-wise passenger aggregation

Visualizations used:
- 📊 Bar Charts
- 📈 Line Charts
- 📉 Histograms

---

## ⭐ Route Popularity Detection

Route popularity is determined by:
- Grouping data by route
- Summing total passengers per route
- Ranking routes based on passenger volume

Routes with higher passenger counts are considered more popular.

---

## 🖥️ Frontend Integration

An interactive frontend is built using **Gradio**, which allows users to:

- Select a route
- Choose transport type
- Enter passenger count
- View live route popularity analysis
- See updated bar charts instantly

This makes the project more practical and user-friendly.

---

## ▶️ How to Run the Project

### Step 1: Open Google Colab
Create a new notebook or open the provided notebook file.

### Step 2: Install Required Library
```bash
pip install gradio

Step 3: Run the Notebook

Execute all cells sequentially.

Step 4: Launch Frontend

A Gradio interface will open where you can provide input and view live analysis.

📈 Results & Insights
	•	Popular routes are clearly identified
	•	Passenger trends are easy to understand through graphs
	•	Interactive input improves analysis experience
	•	Project demonstrates practical EDA skills

⸻

🎓 Learning Outcomes

Through this project, I learned:
	•	How to perform structured EDA
	•	How to visualize real-world datasets
	•	How to rank and analyze categorical data
	•	How to integrate backend logic with a frontend
	•	How to build interactive analytical applications

⸻

🚀 Future Enhancements
	•	Use real-world public transport datasets
	•	Add machine learning models for ridership prediction
	•	Deploy as a web application using Flask or Streamlit
	•	Integrate database for persistent storage
	•	Expand dashboard for smart city analytics

⸻

📄 License

This project is created for educational purposes as part of an academic AI/ML Minor project.

⸻

🙌 Acknowledgement

I would like to thank my faculty and mentors for guidance and support throughout this project.

⸻


