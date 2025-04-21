# ✈️ British Airways Data Science Virtual Experience (Forage)

This repository contains the end-to-end implementation of tasks completed as part of the **British Airways Data Science Virtual Experience Program** on [Forage](https://www.theforage.com/). The program simulates real-world challenges faced by airline data teams, focusing on customer insights, predictive analytics, and business decision support.

---

## 📌 Program Overview

British Airways, a global airline, is committed to leveraging data to enhance customer experience and operational efficiency. This project involves two core business use cases:

### 1. Web Scraping & Sentiment Analysis
Gain insights from customer feedback by scraping and analyzing unstructured reviews from external sources (Skytrax).

### 2. Predictive Modeling on Customer Bookings
Use structured booking data to predict which customers are most likely to purchase holiday packages, enabling better targeting and personalization.

---

## 🧱 Project Structure

```bash
├── ba_reviews_analysis/
│   ├── scrape_reviews.ipynb
│   ├── sentiment_analysis.ipynb
│   ├── ba_reviews.csv
│   ├── wordcloud.png
│   ├── sentiment_distribution.png
│   └── review_insights_slide.pptx
│
├── holiday_prediction_model/
│   ├── holiday_prediction_model.ipynb
│   ├── customer_bookings.csv (simulated)
│   ├── holiday_feature_importance.png
│   └── holiday_purchase_model_slide.pptx
│
├── README.md
└── LICENSE
```

# 🔍 Task 2: Predictive Modeling of Holiday Purchases

## 🎯 Objective
Build a predictive model to identify which customers are likely to purchase holiday packages based on their booking behaviors.

---

## 📁 Dataset (Simulated)

**Total Records**: ~500 rows of synthetic customer booking data

**Fields Included**:
- `age`
- `membership_status` (Bronze, Silver, Gold)
- `price`
- `destination` (Europe, Asia, North America, etc.)
- `booking_channel` (Website, Mobile App, Travel Agent)
- `days_until_departure`
- `previous_bookings`
- `holiday_purchase` (Target label)

---

## 🧪 Steps Performed

- ✅ Preprocessed the data using `pandas`
- ✅ Handled missing values and cleaned inconsistencies
- ✅ Applied one-hot encoding to categorical features
- ✅ Built a `RandomForestClassifier` using `scikit-learn`
- ✅ Evaluated the model using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
- ✅ Interpreted feature importance using `.feature_importances_`

---

## 📈 Key Features Impacting Holiday Purchases

| Feature                  | Insight                                                             |
|--------------------------|---------------------------------------------------------------------|
| `price`                 | Lower fares correlated with higher holiday purchase probability     |
| `membership_status_Gold`| Loyal customers had higher conversion rates                         |
| `days_until_departure`  | Early bookings led to higher holiday conversions                    |
| `previous_bookings`     | Repeat customers were more likely to add holiday packages           |
| `destination_Europe`    | Europe was the top-performing region for holiday purchases          |

---

## 📌 Model Performance

- **Model Type**: Random Forest Classifier  
- **Accuracy**: ~78% on test data  
- **Split**: 80% train / 20% test  
- **Hyperparameters**: Default (n_estimators=100, random_state=42)

---

## 🖼️ Outputs

- `customer_bookings.csv` – Simulated booking dataset
- `holiday_feature_importance.png` – Top features driving predictions
- `holiday_purchase_model_slide.pptx` – Business summary slide deck

---

## 🧠 Key Skills Practiced

### 👨‍💻 Technical Skills
- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Random Forest Modeling
- Visualizations & Plotting
- Slide Automation (`python-pptx`)

### 💡 Business/Data Skills
- Translating model output into stakeholder-ready insights
- Customer segmentation logic
- Targeted marketing strategy from data signals
- Visual storytelling and dashboard thinking

---

## ⚠️ Challenges Faced

- ❌ Broken HTML parsing from Skytrax during scraping  
  ✔️ Resolved using updated `BeautifulSoup` selectors

- ❌ Missing Python packages in notebook environment  
  ✔️ Fixed by switching to Google Colab and using `!pip install`

- ❌ Model biased towards non-buyers initially  
  ✔️ Resolved by ensuring better train/test balance and tuning

- ❌ Communicating technical output to non-technical audience  
  ✔️ Addressed through slide design, visuals, and simplified language

---

## 📑 Certificate

This project was completed as part of the  
**British Airways Data Science Virtual Experience Program**  
hosted on [Forage](https://www.theforage.com/).

🎓 [View Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/tMjbs76F526fF5v3G/NjynCWzGSaWXQCxSX_tMjbs76F526fF5v3G_7eBNvXPW8jcp6qfxF_1745190476565_completion_certificate.pdf)

---

## 📬 Contact

**Ashish Tammana**  
🔗 [LinkedIn](https://www.linkedin.com/in/ashishtammana)  
📧 tammanaashish0@gmail.com  
🌍 Melissa, Texas

---

