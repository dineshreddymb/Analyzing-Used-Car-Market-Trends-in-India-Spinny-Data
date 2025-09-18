# 🚗 Spinny Used Car Price Analysis
📌 Project Overview
--------------------------------------
This project focuses on scraping used car data from the Spinny website and performing Exploratory Data Analysis (EDA) to uncover insights about car prices, availability, and trends across major Indian cities.

The goal was to analyze how factors like brand, fuel type, transmission, kilometers driven, and city affect used car prices and to identify pricing patterns in the Indian used-car market.

🛠️ Tech Stack
--------------------------------
Python
Selenium (for automated web scraping)
*BeautifulSoup (HTML parsing)
*Pandas / NumPy (data cleaning & analysis)
*Matplotlib / Seaborn (visualizations)

📊 Steps in the Project
--------------------------------
*Web Scraping
*Scraped car listings from Spinny for multiple cities (Delhi, Bangalore, Mumbai, Hyderabad, Chennai, Pune, Kolkata, etc.).
*Extracted details:
*Car Name
*Price
*Kilometers Driven
*Fuel Type
*Transmission
*City & Location
*EMI (if available)
Data Cleaning
-------------------
*Converted price strings (like ₹4.92 Lakh) into numerical values.
*Removed duplicates & missing values.
*Standardized features (Fuel, Transmission, KMS).
*Exploratory Data Analysis (EDA)
*Most popular car brands & models.
*City-wise car distribution.
*Fuel type vs price trends.
*Manual vs Automatic transmission analysis.
*Top expensive cars & most affordable cars.
*Kilometers driven vs price relation.

Insights
--------------------
*🚘 Most listed brands: (e.g., Maruti, Hyundai, Honda).
*📍 City with max listings: (e.g., Delhi NCR).
*⛽ Fuel Trend: Petrol cars dominate, but Diesel & EVs are rising.*
*⚙️ Transmission: Manual cars are more common, but Automatics are priced higher.
*💰 Price Range: Majority of used cars fall between ₹3–10 Lakh.

📈 Visualizations
----------------------
*Some of the key charts created:
*Bar plots of car counts by brand and city.
*Distribution of fuel type and transmission.
*Scatter plots of price vs kilometers driven.
*Boxplots of price distribution across cities.

📂 Files
----------------------
*Project spinny.ipynb → Main Jupyter Notebook with scraping, cleaning & EDA.
*spinny_project.csv → Scraped dataset of used cars.

🚀 Future Work
-----------------------

Build a price prediction model (ML) for used cars.

Compare Spinny vs Cars24 vs OLX Autos datasets.

Deploy as a dashboard in Power BI / Streamlit.
