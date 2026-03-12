![Python](https://img.shields.io/badge/Python-3.9-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-green)
![Plotly](https://img.shields.io/badge/Visualization-Plotly-lightblue)

# 🚀 SpaceX Launch Data Analysis & Prediction

This project is part of the IBM Data Science Capstone.  
It explores SpaceX launch data to identify factors influencing mission success and builds predictive models.

## 📊 Key Findings
- Payload mass and orbit strongly influence launch success.
- Certain booster versions are more reliable.
- Decision Tree model achieved highest accuracy (~83%).

## 📂 Repository Structure
- `notebooks/` → Jupyter notebooks for each stage (API, scraping, wrangling, EDA, ML).
- `app/` → Plotly Dash app for interactive visualization.
- `data/` → Datasets used in analysis.
- `screenshots/` → Visual outputs (maps, dashboards, confusion matrix).

## 🛠 Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- SQL (SQLite)
- Visualization: Matplotlib, Seaborn, Folium, Plotly Dash
- Tools: Jupyter Notebook, GitHub

## 📊 Screenshots of Results
*(Add images into the `screenshots/` folder and link them here)*

- **Folium Map – Global Launch Sites**  
  ![Folium Map](screenshots/folium_map.png)

- **Plotly Dashboard – Launch Success Pie Chart**  
  ![Dashboard Piechart](screenshots/dashboard_piechart.png)

- **Confusion Matrix – Best Performing Model**  
  ![Confusion Matrix](screenshots/confusion_matrix.png)

## ▶️ Instructions to Run
1. Clone the repository:
   git clone https://github.com/febin94/spacex-capstone-project.git
   cd spacex-capstone-project
3. Install dependencies:
   pip install -r requirements.txt
5. Run Jupyter notebooks:
   jupyter notebook
7. Launch the Plotly Dash app:
   spacex-dash-app.py

## 👨‍💻 Author
**Febin** – BCA Graduate, aspiring Data Scientist & ML Engineer  
IBM Data Science Professional Certificate

## 📑 Data Sources
The datasets used in this project were provided as part of the 
[IBM Data Science Professional Certificate Capstone Project](https://www.coursera.org/professional-certificates/ibm-data-science).
