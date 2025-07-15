# 🚗 Scraping Cars24: Extracting Key Insights from Used Car Listings

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![Libraries](https://img.shields.io/badge/Libraries-pandas%2C%20numpy%2C%20matplotlib%2C%20seaborn%2C%20BeautifulSoup-orange)]()  

This project scrapes **Cars24** used car listings to extract, clean, and analyze key data points.  
The analysis reveals **price trends, brand performance, and mileage correlations**, providing valuable insights for car buyers, sellers, and automotive market researchers.

---

## 📌 Table of Contents

1. [Project Overview](#-project-overview)  
2. [Technologies Used](#-technologies-used)  
3. [Project Structure](#-project-structure)  
4. [Installation & Usage](#-installation--usage)  
5. [Sample Insights](#-sample-insights)  
6. [Future Enhancements](#-future-enhancements)  
7. [Contributing](#-contributing)  
8. [Author](#-author)

---

## 📌 Project Overview

- **Objective**: Scrape and analyze Cars24 used car data to identify key market patterns.  
- **Key Features**:  
  ✅ Web scraping Cars24 listings (brand, model, year, mileage, price, fuel type)  
  ✅ Cleaning and preprocessing data  
  ✅ Exploratory Data Analysis (EDA) with visualizations  
  ✅ Price trends, brand-wise comparison, mileage-price correlation  

---

## 🛠 Technologies Used

- **Python** (3.8+)  
- **Libraries**:  
  - `requests`, `BeautifulSoup` – Web scraping  
  - `pandas`, `numpy` – Data cleaning & manipulation  
  - `matplotlib`, `seaborn` – Visualizations  

---

## 📂 Project Structure

```
Scraping-Cars24-Extracting-Key-Insights-from-Used-Car-Listings/
│
├── data/                  # Raw and cleaned data (CSV files)
├── notebooks/             # Jupyter notebooks for scraping & EDA
├── scripts/               # Python scripts for scraping & cleaning
├── images/                # Charts & visualizations
├── requirements.txt       # Project dependencies
└── README.md              # Documentation
```

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/DnyandeepDhande/Scraping-Cars24-Extracting-Key-Insights-from-Used-Car-Listings.git
cd Scraping-Cars24-Extracting-Key-Insights-from-Used-Car-Listings
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Scraper
```bash
python scripts/scrape_cars24.py
```
*(or open the Jupyter notebook in `notebooks/` folder)*

### 4️⃣ Analyze Data
Use the EDA notebook to generate charts and extract insights.

---

## 📊 Sample Insights

✅ **Price Distribution** – Average price trends across brands  
✅ **Brand Comparison** – Popular brands & resale value  
✅ **Mileage vs. Price** – Correlation between mileage and price  
✅ **Fuel Type Trends** – Dominant fuel types in resale market  


---

## 🔥 Future Enhancements

- Automate periodic scraping  
- Build an interactive dashboard (Power BI or Plotly Dash)  
- Predictive modeling for car price estimation  

---

## 🤝 Contributing

Contributions are welcome!  
1. Fork this repository  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Added new feature"`)  
4. Push and submit a PR

---

## 🧑‍💻 Author

**Dnyandeep Dhande**  
[![GitHub](https://img.shields.io/badge/GitHub-DnyandeepDhande-black?logo=github)](https://github.com/DnyandeepDhande)
