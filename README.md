# British_Airways-Data_Science
In this Data Science job simulation, I leveraged Python to execute an end-to-end project—starting with web scraping, followed by data cleaning, organization, and analysis. I then applied statistical modeling to predict customer behavior, gaining hands-on experience in real-world data challenges.

# Airline Feedback Data Analysis

## Introduction
This project focuses on systematically scraping website feedback related to airline services, ensuring no critical details are missed. After scraping, the data undergoes cleaning, missing value imputation, and analysis. 

Based on Exploratory Data Analysis (EDA) and data modeling, a machine learning model is developed to understand key elements that influence customer recommendations for the airline.

---

## Key Questions
- What are the key factors influencing customer recommendations for the airline?
- How have different service aspects evolved over time?
- What insights can be drawn from customer feedback trends?
- Can sentiment analysis effectively capture customer satisfaction levels?

---

## Dataset Summary
The dataset includes various aspects of customer feedback, including:
- **Service Aspects:**
  - Wifi & Connectivity
  - Inflight Entertainment
  - Food & Beverages
  - Cabin Staff Service
  - Seat Comfort
  - Ground Service
- **Flight Details:**
  - Date flown
  - Route
  - Aircraft
  - Cabin flown
- **Customer Details:**
  - Verified status
  - Type of traveler
  - Recommended status
  - Name & Title
- **Additional Features:**
  - Value for Money
  - Feedback text & word count
  - Year & Month of review

![Model Data Description](https://github.com/user-attachments/assets/4f585496-b707-4c0f-85d8-ed82b8bed4c9)

---

## Steps and Tools Used
### Data Collection & Preprocessing
- **Web Scraping:** Extracting feedback systematically.
- **Reading & Cleaning Data:**
  - Handling missing values
  - Standardizing data formats

### Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Identifying trends in individual features.
- **YOY (Year-over-Year) Change Analysis**: Tracking feedback evolution.
- **Word Cloud Analysis**: Extracting key themes from text reviews.
![Positive Feedback Word Cloud](https://github.com/user-attachments/assets/a98fd33d-3917-42af-978f-2f140f213f78)
![Negative Feedback Word Cloud](https://github.com/user-attachments/assets/7346ef91-44c3-4d12-90e3-66f6a932cd35)
- **Correlation Chart**: post performing Feature Selection.
![Negative Feedback Word Cloud](https://github.com/user-attachments/assets/99387564-711d-43ba-88a7-a8cc40771ffc)

- **Feature Scaling & Standardization**: Preparing data for modeling.

### Model Analysis
#### **Sentiment Analysis Approaches:**
- **VADER Sentiment Scoring** (Baseline sentiment analysis)
- **Huggingface Model – Roberta (Pretrained Model)** (Advanced NLP approach)

Why Chosen Roberta Pretrained Model Over VADER ?![image](https://github.com/user-attachments/assets/b88f0080-3f83-467f-a5bc-9beb1b073d97)

**Results:** The **Roberta Model** demonstrated superior accuracy in sentiment analysis compared to VADER.

#### **Regression Models for Predicting Recommendations:**
- **Linear Regression:**  
  - Mean Squared Error: **0.0378**  
  - R-squared: **0.815**
- **Ridge Regression:**  
  - Mean Squared Error: **0.0378**  
  - R-squared: **0.815**


---

## Insights
1. **Service Quality Trends:**
   - **Cabin Staff Service** ratings declined in 2024 compared to 2023, indicating a possible service quality drop.
   - **Food & Beverages** saw an upward trend, suggesting improved customer satisfaction.
   - **Ground Service** consistently received low ratings, requiring urgent attention.
   - **Inflight Entertainment & Seat Comfort** showed slight improvements.
   - **Value for Money** increased in 2024 compared to 2023.
   - **Wifi & Connectivity**, which faced issues in 2023, showed the most significant improvement.

![In 2024, British Airline enhanced customer satisfaction by improving at 5 services out of 8 compared to 2023, as mentioned on this chart](https://github.com/user-attachments/assets/f6bf1433-a247-4556-bcf3-4299af09cf86)


2. **Passenger Preferences:**
   - More passengers shifted from **Economy Class** to higher classes, possibly influencing improved ratings.
   - A slight increase in **non-verified user reviews** was observed in 2024.
   - **Recommendation counts** showed a modest rise in 2024.

3. **Potential Concerns:**
   - A general decline in ratings could indicate reduced passenger volume, changes in the survey process, or degraded service quality.

---

## Conclusion
- The feedback count in 2024 is lower than in 2023.
- A slight increase in non-verified users and recommendations was observed.
- Declining ratings suggest either fewer passengers, a change in survey methodology, or deteriorating service quality.

---

## Recommendations for 2025
- **Reverse service quality decline** by addressing key concerns.
- **Focus on moderate satisfaction areas (ratings of 3 and 4)** to convert them into high satisfaction.
- **Increase survey participation** for richer insights.
- **Enhance services** to maintain consistent and high ratings.

---

## How to Use This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   python analysis.py
   ```

---

## Future Enhancements
- Expand dataset with more historical data.
- Explore deep learning approaches for text analysis.
- Automate feedback collection and updates.

---

### 📌 Author: *Jignesh*
🚀 Connect with me on [LinkedIn](https://www.linkedin.com/in/jigneshmore/) | ✉ Contact me at [Email](jigneshmore5445@gmail.com)


