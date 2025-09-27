# Smart Campus Energy Optimizer

## 📖 Overview

This project is an end-to-end data science application designed to predict and optimize electricity consumption. It analyzes historical energy usage data, trains a machine learning model to forecast future demand, and provides actionable, rule-based suggestions for energy conservation through an interactive web dashboard.

This project was built as a Final Year Project, demonstrating skills in data cleaning, time-series analysis, machine learning, and application development.

![Dashboard Screenshot](<img width="1913" height="923" alt="Screenshot 2025-09-27 222806" src="https://github.com/user-attachments/assets/1ada44d3-95cb-4ca9-a45f-200a0c2ac710" />
)
*You should replace the line above with a screenshot of your running dashboard.*

---

## ✨ Key Features

* **Data Cleaning & Preparation:** Processes raw, minute-by-minute energy data into a clean, daily-aggregated dataset.
* **Machine Learning Model:** Utilizes a **Random Forest Regressor** to predict daily `Global_active_power` based on time-based features (year, month, day, day of week).
* **Forecasting:** Implements a **Prophet** model to forecast energy demand for the next year.
* **Rule-Based Optimization:** Generates simple energy-saving suggestions (e.g., reducing load on high-usage weekends).
* **Interactive Dashboard:** A web application built with **Streamlit** that allows users to:
    * Select a date range.
    * Visualize actual vs. predicted energy usage.
    * View actionable conservation tips for the selected period.

---

## 🛠️ Technology Stack

* **Language:** Python 3.9+
* **Core Libraries:** Pandas, NumPy, Scikit-learn
* **Time-Series Forecasting:** Prophet
* **Dashboard:** Streamlit
* **Plotting:** Matplotlib
* **Environment:** Jupyter Notebook (for exploration), VS Code (for application development)

---

## 🚀 How to Run the Dashboard

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/smart-campus-energy-optimizer.git](https://github.com/YOUR_USERNAME/smart-campus-energy-optimizer.git)
    cd smart-campus-energy-optimizer
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # Create the environment
    python -m venv venv

    # Activate on Windows
    venv\Scripts\activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Streamlit application:**
    ```bash
    streamlit run dashboard/app.py
    ```
    The application will open in a new tab in your web browser.

---

## 📂 Project Structure
