# Pharmacy Database - Integrated System Instructions

This project is a fully integrated Pharmacy Database Management System. It contains both a **Jupyter Notebook** for data science analysis and a **Flask Web Frontend** for data management.

## Prerequisites

To run this project, you will need:
- Python 3.8+
- The required libraries: `Flask`, `pandas`, `nbformat`, `nbconvert`, `ipykernel`, `ipywidgets`

Install everything at once by running:
```bash
pip install -r requirements.txt
```

## How to Run

### 1. The Web Frontend (Flask App)
The web interface allows you to manage pharmacies, medicines, customers, and purchases through a professional dashboard.

1. Open your terminal in this folder.
2. Run the application:
   ```bash
   python app.py
   ```
3. Open your browser to `http://127.0.0.1:5000`.

### 2. The Data Analysis (Jupyter Notebook)
The notebook is used for deep data analysis, Kaggle data loading, and presentation-ready reports.

1. Open `Pharmacy_Database.ipynb` in VS Code or Jupyter.
2. Click **Run All** to initialize the database and see the analytics.

## Shared Database
The Notebook and the Web Frontend share the **exact same** `pharmacy_database.db` file. 
- Updates made in the web app will show up in the notebook analytics.
- Data loaded via the notebook (e.g., from Kaggle) will be visible on the website.

## Project Structure
- `app.py`: The main Flask web application script.
- `templates/`: HTML templates for the web interface.
- `Pharmacy_Database.ipynb`: The data science and analysis notebook.
- `pharmacy_database.db`: The shared SQLite database file.
- `Pharmacy Data/`: Raw data files (including Kaggle datasets).
- `requirements.txt`: List of Python dependencies.
