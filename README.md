# 🎧 Spotify DataOps: Database Administration & Recommendation System

This project implements a complete **Data Operations (DataOps)** pipeline for Spotify data, covering rigorous database administration, advanced analytics, and a machine learning recommendation system.

## ✨ Core Functionality

This solution provides a full-cycle data workflow:

1.  **Data Ingestion & Preprocessing:**
    * Crawling raw Spotify data and loading it via SQL scripts.
    * Using **SQL Stored Procedures/Functions/Triggers** for robust data cleansing and transformation.
2.  **Advanced Database Administration:**
    * **Data Backup:** Detailed backup procedures (type, schedule, storage device management).
    * **Authorization:** Full **Role-Based Access Control (RBAC)** implementation via SQL commands.
3.  **Analytics & Visualization:**
    * Generating insights using **Power BI** dashboards (`.pibx`).
    * Building interactive data exploration applications with **Python Streamlit**.
4.  **Machine Learning:**
    * Developing and integrating a **Song Recommendation Model** to suggest music based on user preferences.

## 🚀 Tech Stack Highlights

| Category | Tools/Language | Focus |
| :--- | :--- | :--- |
| **Data Platform** | SQL (Procedures, Triggers) | DB Administration, ETL, Security. |
| **Data Science** | Python (Scikit-learn) | ML Model Development. |
| **Application** | Streamlit | Interactive Web Interface. |
| **Reporting** | Power BI, Jupyter Notebook | Dashboarding and EDA. |

## ⚙️ Quick Start

### 1. Prerequisites
* SQL Database (e.g., PostgreSQL/MySQL)
* Python 3.x with dependencies: `pandas`, `scikit-learn`, `streamlit`

### 2. Run the Application
Execute the Streamlit app to view visualizations and interact with the recommendation model:

```bash
streamlit run Spotify_Streamlit.py
```
### 3. Key Files

| File | Purpose |
| :--- | :--- |
| `Spotify_Scrape data...sql` | Initial data loading. |
| `Spotify_Preprocessinng.sql` | Data transformation logic. |
| `Spotify_BackupData.sql` | Database backup routine. |
| `Spotify_Decentralization_Database.sql` | Authorization and user role setup. |
| `Spotify_Dashboard.pibx` | Power BI dashboard file. |
| `Spotify_Visualization_With_Python.ipynb` | Visualization. |
