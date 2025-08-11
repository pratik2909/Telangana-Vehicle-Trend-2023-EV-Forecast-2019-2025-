Telangana Vehicle Trends (2023) & EV Forecast (2019–2025)
By Pratik Bose

📌 Overview
This project provides a two-phase analysis to decode Telangana’s mobility landscape:

Comprehensive Registration Analysis – All vehicle registrations in Telangana for 2023.

Electric Vehicle Forecasting – EV registration projections based on historical data from 2019–2025.

Using Python-based analytics and forecasting tools, the study reveals market trends, seasonal peaks, brand performance, and a predictive outlook for EV adoption.

🛠 Tech Stack & Tools
Languages: Python

Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn, Facebook Prophet

Data Source: Telangana State Transport Registration Data (Excel)

📂 Dataset Structure
1. 2023 Vehicle Registration Dataset

Source: Telangana transport registration monthly Excel sheets

Format: 12 monthly sheets consolidated into a single dataset

Key Columns: Maker, Model, Fuel Type, Registration Count, Region

2. EV Dataset (2019–2025)

Focused exclusively on EV registrations

Contains brand, model, registration count, and month/year

⚙ Data Preparation
Monthly Sheet Combination – Unified 12 monthly sheets for 2023 into one dataset

Column Name Standardization – Ensured uniform naming

Month Column Creation – Added for time-series analysis

Missing Value Handling – Removed/imputed missing data

Time-Series Conversion (EV dataset) – Monthly aggregation and lag feature creation for forecasting models

🔍 Key Insights – 2023 Analysis
Seasonal Peaks: Oct–Dec and March saw the highest registrations (festive season & financial year-end)

Market Share: Dominated by a few brands such as Honda, Bajaj Auto, TVS Motors, Hero Moto, Maruti Suzuki

Regional Differences: Some districts showed significantly higher registrations than others

📈 EV Forecasting – 2019 to 2025
Models Used:

Random Forest Regressor – Captured non-linear trends using feature-based prediction

Facebook Prophet – Modeled seasonality and long-term growth trends

Evaluation Metrics:

RMSE (Root Mean Squared Error)

R² (Coefficient of Determination)

Results:

Prophet Model: Predicts steady EV growth through 2025

Random Forest: Closely aligns with actual data, validating accuracy

Seasonal dips mid-year, with peaks around Oct–Dec and March

📌 Conclusions & Recommendations
Telangana’s overall vehicle market is steadily growing

EV adoption is accelerating, signaling a shift to sustainable mobility

Recommendations:

Expand EV charging infrastructure

Target marketing before seasonal peaks

Increase EV dealership coverage in low-registration regions

📧 Author
Pratik Bose
📍 Bangalore,Karnataka
📩 pratikbose72@gmail.com
🔗 https://www.linkedin.com/in/pratikbose0009/
