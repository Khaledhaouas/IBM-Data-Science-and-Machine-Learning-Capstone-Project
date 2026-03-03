# Applied Data Science Capstone Project  

## Overview  

This project focuses on predicting whether the Falcon 9 first stage lands successfully.

SpaceX advertises Falcon 9 launches at around $62M, significantly lower than competitors that can exceed $165M per launch. A major reason for this difference is reusability — if the first-stage booster lands successfully, it can fly again, dramatically reducing launch costs.

By predicting landing success, we can indirectly estimate cost efficiency and generate insights that could be useful for companies competing with SpaceX in launch bids.

---

## Project Objectives  

The project follows a complete end-to-end data science workflow — from raw data collection to model evaluation.

### 1. SpaceX API & Data Wrangling  

- Collected historical Falcon 9 launch data via the SpaceX API  
- Cleaned and formatted the dataset  
- Handled missing values and ensured consistency  

### 2. Web Scraping Launch Records  

- Scraped additional Falcon 9 launch data from Wikipedia using BeautifulSoup  
- Parsed HTML tables and converted them into Pandas DataFrames  

### 3. Exploratory Data Analysis (EDA)  

- Used Matplotlib and Seaborn to analyze launch outcomes, payload trends, and site performance  
- Identified patterns and correlations influencing landing success  
- Defined the target label for machine learning  

### 4. Database Integration  

- Loaded the dataset into a Db2 database  
- Used SQL queries for structured analysis and insight generation  

### 5. Feature Engineering & Geographical Visualization  

- Engineered new features to improve predictive performance  
- Built interactive maps using Folium to visualize launch sites and outcomes  

### 6. Interactive Dashboard (Plotly Dash)  

- Developed a Plotly Dash application for interactive data exploration  
- Added dropdowns and range sliders for dynamic filtering  
- Enabled real-time analysis of success rates and payload distributions  

### 7. Machine Learning & Model Tuning  

- Standardized features and split data into training and test sets  
- Trained multiple classifiers (Logistic Regression, SVM, KNN, Decision Trees)  
- Tuned hyperparameters using GridSearchCV  
- Evaluated and compared model performance  

---

## Results  

- **Decision Tree Classifier** achieved the highest accuracy: **0.9444**  
- **SVM** and **KNN** both achieved **0.8333** accuracy  

The Decision Tree model was selected as the best-performing approach for landing prediction.

---

## Conclusion  

This project demonstrates a full data science pipeline — from API extraction and web scraping to interactive analytics and predictive modeling.

The final model provides a solid framework for estimating Falcon 9 landing success and understanding cost efficiency drivers.

---

## Repository Structure  

- `presentaion/` – Final Presentation file
- `notebooks/` – Jupyter notebooks documenting each stage  
- `README.md` – Project documentation  

---

## Acknowledgments  

- **IBM** – Applied Data Science Program  
- **edX** – Learning platform  
