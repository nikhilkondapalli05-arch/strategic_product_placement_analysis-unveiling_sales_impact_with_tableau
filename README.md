<h1 align="center">
📊 Strategic Product Placement Analysis – Unveiling Sales Impact with Tableau
</h1>

<p align="center">
Unveiling Sales Impact using Tableau & Flask
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3.11.2-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Flask-Web_Framework-black?style=for-the-badge&logo=flask">
<img src="https://img.shields.io/badge/Tableau-Data_Visualization-orange?style=for-the-badge&logo=tableau">
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

## 📊 Project Overview

This repository contains a complete end-to-end analytics project that examines product placement and pricing strategy using Tableau visualizations, integrated into a Flask-based web application for interactive analysis.

---

## 🧠 Project Objective

- Analyze product pricing and sales trends across categories.
- Compare average product pricing with competitor benchmarks.
- Generate interactive visualizations to support strategic pricing decisions.
- Create a coherent analytical story using Tableau Story Points.
- Deploy visual output via a simple Flask web application.

---

## Demo Video
[Watch the demonstration video here](https://drive.google.com/file/d/1UrRa1rBkDsd6FXRDKiybGQSnTLyOyr61/preview)

## 🚀 Live Dashboard

🔗 **Tableau Public Dashboard:**  
https://public.tableau.com/views/ProductPlacementAnalysis-SalesImpact/Dashboard-ProductPlacementAnalysis-SalesImpact

 Live Story
🔗 **Tableau Public Story:**  
https://public.tableau.com/views/ProductPlacementAnalysis-SalesImpact/Story-ProductPlacementAnalysis-SalesImpactStory

---


## 📈 Tableau Visualization

### 1️⃣ Interactive Dashboard
- Category pricing comparisons
- Sales impact & competitor analysis
- <img width="1976" height="799" alt="_Dashboard - Product Placement Analysis -Sales Impact" src="https://github.com/user-attachments/assets/40e843c3-fb65-4c4d-b66f-0f51e659caba" />


### 2️⃣ Analytical Story
- Structured business insights
- Strategic recommendations
- Product Placement Analysis
- <img width="1976" height="799" alt="Story - Product Placement Analysis -Sales Impact Story (1)" src="https://github.com/user-attachments/assets/970a1a68-d5da-440d-b3b0-4c67a38f48b2" />


## 🖥 Flask Web Application

### 🧾 app.py

```python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template("index.html")

if __name__ == '__main__':
    app.run(debug=True)
```

---

## 📌 How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/nikhilkondapalli05-arch/strategic_product_placement_analysis-unveiling_sales_impact_with_tableau.git
```

### 2️⃣ Navigate to project directory

```bash
cd strategic_product_placement_analysis-unveiling_sales_impact_with_tableau
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Flask app

```bash
python app.py
```

Open browser and go to:

```
http://localhost:5000
```

---

## 📄 Documentation & Supporting Files

Includes:
- Preprocessing & Business Questions
- Dashboard & Story Screenshots
- Final Report

---

## 🛠 Tools & Technologies Used

| Technology        | Purpose |
|-------------------|----------|
| Python (Flask)    | Web app backend |
| Tableau Desktop   | Dashboard creation |
| Tableau Public    | Publishing dashboards |
| HTML & CSS        | Front-end rendering |
| GitHub            | Version control |

---

## 👨‍💻 Author

PARAPATLA SAI KUMAR 

## Email :
parapatlasai123@gmail.com 
