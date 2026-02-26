<h1 align="center">
📊 Strategic Product Placement Analysis-Unveiling Sales Impact with Tableau

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

The goal is to enable stakeholders to understand pricing differences relative to competitors and explore impactful sales insights through interactive dashboards and story narratives.

---

## 🧠 Project Objective

The purpose of this project is to:

- Analyze product pricing and sales trends across categories.
- Compare our average product pricing with competitor benchmarks.
- Generate interactive visualizations to support strategic pricing decisions.
- Create a coherent analytical story using Tableau Story Points.
- Deploy the visual output via a simple Flask web application.


## 🚀 Live Dashboard
🔗 Tableau Public Dashboard: **[https://public.tableau.com/views/ProductPlacementAnalysis-SalesImpact/Dashboard-ProductPlacementAnalysis-SalesImpact?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]**

🔗 Tableau Public Story: **[https://public.tableau.com/views/ProductPlacementAnalysis-SalesImpact/Story-ProductPlacementAnalysis-SalesImpactStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]**

📦 strategic_product_placement_analysis-unveiling_sales_impact_with_tableau
│
├── 📂 static/ # CSS, JS, images used in web application
├── 📂 templates/ # HTML templates
│ └── index.html
├── 📂 Dataset/ # Source dataset used for analysis
│ └── [dataset file]
├── 📂 PDFs/ # Supporting documentation
│ ├── Preprocessing & Business Questions.pdf
│ └── Dashboard_Story_Webpage_Screenshots.pdf
├── app.py # Flask web server code
├── requirements.txt # Python dependencies
├── README.md # Project overview (this file)
├── Final Report Template.pdf # Final project report template
├── .gitignore
└── LICENSE


# 📈 Tableau Visualization

This project includes:

1. **Interactive Dashboard**
   - Visual representation of category pricing comparisons.
   - Sales impact, pricing gaps, and competitor analysis.
2. **Analytical Story**
   - Structured narrative of business insights.
   - Includes key takeaways and strategic recommendations.

Both Dashboard and Story are published on **Tableau Public** and embedded in the Flask web application.

🔗 **Tableau Public Dashboard Link **  
https://public.tableau.com/views/ProductPlacementAnalysis-SalesImpact/Dashboard-ProductPlacementAnalysis-SalesImpact?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

🔗 **Tableau Public Story Link **  
https://public.tableau.com/views/ProductPlacementAnalysis-SalesImpact/Story-ProductPlacementAnalysis-SalesImpactStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 🖥 Flask Web Application

This project uses Flask (Python) to serve an HTML webpage that embeds both Dashboard and Story visualizations published on Tableau Public.

### 🧾 app.py

The main Flask application file:

```python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template("index.html")

if __name__ == '__main__':
    app.run(debug=True)


📌 How to Run Locally

Clone the repository:

</> Bash
git clone https://github.com/YOUR_USERNAME/strategic_product_placement_analysis-unveiling_sales_impact_with_tableau.git


Navigate to the project directory:

</> Bash
cd strategic_product_placement_analysis-unveiling_sales_impact_with_tableau


Install dependencies:

</> Bash
pip install -r requirements.txt

Run the Flask app:

</> Bash
python app.py


Open browser and go to:

</> Code
http://localhost:5000


Having any Queries :

📄 Documentation & Supporting Files



The PDFs folder includes:

Preprocessing & Business Questions.pdf
Contains data cleaning steps and visualization insights.
Dashboard_Story_Webpage_Screenshots.pdf

Screenshots showing:

Tableau Dashboard
Tableau Story
Flask Web Page


🛠 Tools & Technologies Used


Technology	       Purpose

Python (Flask)	   Web app for embedding analytics
Tableau Desktop	   Dashboard creation
Tableau Public     publish and share dashboards
HTML & CSS        	Front-end rendering
GitHub	           Version control


