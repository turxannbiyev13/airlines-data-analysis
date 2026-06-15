# ✈️ Airlines Flight Price Analysis

## 📌 Project Overview
This project performs an end-to-end data analysis on airline flight data to uncover price dynamics, purchasing behavior, and travel trends. By cleaning, visualizing, and analyzing a dataset of 39,000+ records, this project provides actionable insights into how factors like travel class, booking time, and flight duration impact ticket pricing.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Key Libraries:** Pandas (Data manipulation), NumPy (Numerical computing), Matplotlib & Seaborn (Statistical visualization)

## 📂 Dataset
The original dataset used in this project is hosted externally due to file size constraints. You can access the data files here:

[Download Movie Analysis Dataset from Google Drive](https://drive.google.com/drive/folders/1_-Ofn4r52qiNLO7jvoKc_0MdGe4t4uhX?usp=sharing)

## 📊 Dataset Insights
The dataset contains **39,048 records** and **14 features**, including:
* **Flight Details:** Airline, flight number, source/destination cities, and stops.
* **Pricing Factors:** Travel class (Economy/Business), booking lead time (`days_left`), and duration.
* **Time Metrics:** Departure and arrival time windows.

## 🔍 Key EDA Findings
* **Price Drivers:** Analysis of how flight duration and booking lead time correlate with ticket prices.
* **Segment Comparisons:** Statistical comparison between Economy and Business class pricing.
* **Operational Trends:** Impact of the number of stops on total flight duration and consumer cost.

## 🧹 Methodology
1. **Data Cleaning:** Handling duplicates and managing missing values (NaN) to ensure high data integrity.
2. **Feature Engineering:** Creating `days_left_group` categories to better analyze user booking behavior.
3. **Data Preprocessing:** Optimizing data types (`category`, `float64`) for memory efficiency and faster computation.

## 🚀 How to Run
1. Clone this repository: 
   `git clone https://github.com/turxannbiyev13/airlines-data-analysis.git`
2. Open the `.ipynb` file in Google Colab or Jupyter.
3. Ensure the required libraries are installed: `pip install pandas numpy matplotlib seaborn`

## 📂 Dataset
Due to file size constraints, the original dataset is hosted externally. You can access it here:
[Download Airlines Dataset from Google Drive](PASTE_YOUR_GOOGLE_DRIVE_LINK_HERE)

---
*Created by Turkhan Nabiyev*
