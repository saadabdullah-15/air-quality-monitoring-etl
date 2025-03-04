# 🌍 Air Quality Monitoring ETL Pipeline

![Python](https://img.shields.io/badge/Python-3.9-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Google_Colab-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%2C%20Requests%2C%20Matplotlib%2C%20Folium-lightgrey)

---
![bground](https://github.com/user-attachments/assets/2e21f9e3-2b38-4a72-9dd5-7c515e3c50ca)

This project is an automated ETL (Extract, Transform, Load) pipeline to monitor air quality using real-time data from the **OpenAQ API**.  
I designed and implemented the pipeline in a **Google Colab (Jupyter Notebook)** environment to dynamically analyze and visualize **PM2.5 monitoring locations** across India.

---

## 🚀 Features
- ✅ Real-time data extraction from OpenAQ v3 API.
- ✅ Automated extraction, transformation, and loading (ETL).
- ✅ Authentication using API key.
- ✅ Data cleaning and filtering for PM2.5 sensors.
- ✅ CSV export of filtered PM2.5 location data.
- ✅ Visualizations including:
  - Bar chart of monitoring locations.
  - Interactive map of station locations with detailed popups.

---

## 📊 Tech Stack
- Python
- Pandas
- Requests
- Matplotlib
- Folium
- Google Colab (Jupyter Notebook)

---

## 📂 Project Structure
```
air-quality-monitoring-etl/
│
├── Air_Quality_ETL_Pipeline.ipynb    # Full Colab notebook with ETL pipeline
├── pm25_india_locations.csv          # Cleaned dataset of PM2.5 monitoring locations in India
├── README.md                         # Project documentation
└── requirements.txt (optional)       # Python dependencies
```

---

## 🔹 How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/air-quality-monitoring-etl.git
    ```

2. Open the notebook:
    - Run directly in **Google Colab** or any **Jupyter Notebook** environment.
    
3. Install dependencies (if needed):
    ```bash
    pip install pandas requests matplotlib folium
    ```

4. Run all cells to fetch, process, and visualize the data.

---

## 📈 Future Improvements
- Automate the pipeline on a schedule (daily/weekly updates).
- Deploy as a **Streamlit** or **Gradio** web application.
- Collect historical data for time-series analysis.
- Add AQI prediction using machine learning models.
- Expand to include more pollutants (like PM10, NO2, O3).

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---

## ⭐ Acknowledgments
- [OpenAQ API](https://openaq.org) for providing free, real-time air quality data.

