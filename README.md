# Hotel Booking Cancellation & Revenue Analysis

## Project Overview

This project focuses on analyzing hotel booking behavior, identifying factors that influence booking cancellations, and building machine learning models to predict whether a booking will be canceled.

The project combines:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Cancellation Pattern Analysis
- Revenue Analysis
- Machine Learning Prediction
- Interactive Power BI Dashboard

The goal is to help hotel management reduce cancellation losses, improve revenue planning, and make data-driven business decisions.

---

## Problem Statement

Hotel booking cancellations can significantly impact revenue, occupancy planning, and operational efficiency.

This project aims to:

- Analyze booking trends
- Understand cancellation patterns
- Identify key factors affecting cancellations
- Predict future booking cancellations using machine learning
- Visualize business insights through an interactive dashboard

---

## Dataset Information

The dataset contains hotel booking records including:

- Hotel Type
- Booking Date
- Lead Time
- Market Segment
- Country
- ADR (Average Daily Rate)
- Customer Information
- Reservation Status
- Cancellation Status

Target Variable:

- `is_canceled`
  - 0 = Not Cancelled
  - 1 = Cancelled

---

## Project Workflow

### 1. Data Cleaning

Performed:

- Missing value treatment
- Duplicate removal
- Outlier detection and handling
- Data type corrections
- Feature preparation

---

### 2. Exploratory Data Analysis (EDA)

Key analyses performed:

#### Cancellation Rate Analysis

- Analyzed overall cancellation percentage.
- Identified canceled vs non-canceled booking distribution.

#### ADR vs Cancellation

- Studied relationship between room price and cancellation.
- Higher ADR bookings showed increased cancellation tendency.

#### Lead Time Analysis

- Customers booking far in advance were more likely to cancel.

#### Seasonal Trend Analysis

- Compared booking behavior across months.
- Identified peak booking seasons.

#### Correlation Analysis

- Used heatmaps to understand relationships between variables.
- Lead Time and Previous Cancellations showed notable impact.

---

### 3. Feature Engineering

Applied:

- Label Encoding
- Feature Selection
- Target Separation

---

### 4. Machine Learning Models

#### Logistic Regression

Used as baseline classification model.

Metrics Evaluated:

- Accuracy
- Precision
- Recall
- ROC-AUC Score

---

#### Decision Tree Classifier

Used to capture non-linear patterns in booking behavior.

Metrics Evaluated:

- Accuracy
- Precision
- Recall
- ROC-AUC Score

---

## Dashboard Overview

An interactive Power BI dashboard was developed for business users.

### KPI Cards

- Total Bookings: 85K
- Cancellation Rate: 27.16%
- Average Lead Time: 80.15
- Average ADR: 101.79

### Dashboard Insights

#### Booking Trends by Month

- Peak bookings observed during July and August.
- Seasonal demand fluctuations clearly visible.

#### Cancellation Rate by Hotel Type

- City Hotel: 29.95%
- Resort Hotel: 22.61%

City hotels experience higher cancellation rates.

#### Cancellation Rate by Market Segment

Highest cancellation rates observed in:

- Online Travel Agencies
- Groups Segment

Lower cancellation rates observed in:

- Direct Bookings
- Corporate Bookings

#### Country-wise Booking Analysis

Top contributing countries:

- Portugal (PRT)
- United Kingdom (GBR)
- France (FRA)
- Spain (ESP)

#### ADR Analysis

Canceled bookings show slightly higher average ADR compared to non-canceled bookings.

---

## Key Findings

### Business Insights

- Approximately one-fourth of bookings are canceled.
- Long lead times increase cancellation probability.
- Higher ADR bookings are more likely to be canceled.
- City hotels face greater cancellation risk than resort hotels.
- Online booking channels contribute most cancellations.
- Summer months generate highest booking volume.

---

## Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Visualization

- Power BI

### Machine Learning

- Logistic Regression
- Decision Tree Classifier

---

## Project Structure

```text
Hotel-Booking-Cancellation-Analysis/
│
├── Data/
│   ├── hotel_bookings_dataset.csv
│   └── hotel_bookings_cleaned.csv
│
├── Notebooks/
│   ├── Hotel Booking Analytics & Cancellation Prediction.ipynb
│   ├── Hotel Booking EDA & Analysis.ipynb
│   └── Hotel Booking Cancellation Prediction.ipynb
│
├── Models/
│   └── cancellation_model.pkl
│
├── Dashboard/
│   └── Hotel Booking Cancellation & Revenue Analysis Dashboard.pbix
│
└── README.md
```
## Conclusion

This project demonstrates how data analytics and machine learning can be used to understand hotel booking behavior, reduce cancellation-related losses, and improve revenue management. The combination of EDA, predictive modeling, and Power BI visualization provides actionable insights for hotel business stakeholders.
```
## Author

**Tanmay Paul**  
Data Science Enthusiast | Aspiring Data Analyst
Intern in Infotect
```
