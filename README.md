# 🤖 **BudgetSense-AI — AI/ML**

Turning India’s Union Budget Into Economic Intelligence

---

## 📌 **Project Mission**

The Union Budget is one of India’s most critical financial statements, shaping national priorities, sectoral growth, and economic development. However, analyzing the vast mixture of numerical data, policy text, and sector information manually is extremely challenging.

**BudgetSense-AI automates this analysis using AI & ML**, transforming raw budget documents into:

* Structured policy insights
* Sector-wise intelligence
* Trend and theme detection
* Predictive indicators
* Easy-to-understand visuals

This project applies AIML to make budget analysis **efficient, data-driven, and actionable** — bringing clarity to one of the most important documents of India’s economy.

---

# 🔍 **Insight Highlights**

## 🧠 **Text Analysis Module — *Completed***

### 📄 Data Extraction & Preparation

✔ Extracted complete Union Budget 2024–25 speech from government PDFs
✔ Cleaned and converted into structured paragraphs + 800+ sentences
✔ Removed noise: URLs, symbols, punctuation, stopwords
✔ Performed tokenization + lemmatization

### 🏷️ Entity Recognition

Detected key financial and policy components including:

* Ministries (Finance, Education, Health, Agriculture, Defence)
* Sectors (Agriculture, Digital, Green Energy, Social Welfare, Infrastructure)
* Schemes & policy initiatives
* Monetary allocations (standardized to ₹ crore)
* Percentages (growth, allocation changes, fiscal statistics)

### 🎯 Keyword & Theme Intelligence

Using TF-IDF + LDA Topic Modeling, major themes identified include:

* Infrastructure & CapEx
* Tax reforms
* Digital economy development
* Green energy transition
* Social welfare schemes

### 📊 Categorization & Insights

✔ Classified text into sectors, policies, investments
✔ Extracted sector allocations & policy focus areas
✔ Built structured datasets to support forecasting & dashboards

This module forms **the core intelligence engine of BudgetSense-AI**, converting complex policy text into meaningful data.

---

## 💬 **Sentiment Analysis Module — *Upcoming***

 ### Purpose

To analyze **public and media sentiment** toward Union Budget announcements.

### Planned Features

* Collect reactions from news articles, tweets, and financial commentary
* Classify sentiment as **Positive / Negative / Neutral**
* Map sentiment across sectors & key policies
* Support decision-making via public feedback understanding

This module will bring a **behavioral perspective** to economic policy analysis.

---

## 🔮 **Numerical Forecasting Module — *Upcoming***

### Purpose

Predict economic indicators and sectoral trends using historical budget data.

### Planned Features

* Regression models
* Time-series forecasting (ARIMA, Prophet)
* Sector-wise budget prediction
* Growth projections for key policy areas

### Expected Outcomes

* Forecasted budget values for ministries
* Trendlines for economic metrics
* Data-driven expectations for future fiscal directions

This will add **predictive intelligence** to the system.

---

## 🌐 **Web Deployment / Dashboard Module — *Upcoming***

### Purpose

Provide an **interactive dashboard** for users to explore:

* Sector allocations
* Policy themes
* Sentiment heatmaps
* Forecasting charts

### Tools

Flask / Streamlit • Matplotlib • WordCloud • Plotly

This module will make insights accessible to **policymakers, analysts, and students** in one place.

---

# 🛠️ **Tech Stack & Skills Demonstrated**

| Area                 | Applied Skills                                                |
| -------------------- | ------------------------------------------------------------- |
| **Data Handling**    | PDF Parsing, Text Cleaning, Preprocessing                     |
| **NLP**              | Tokenization, NER, Keyword Extraction, Topic Modeling         |
| **Machine Learning** | Classification (upcoming), Time Series Forecasting (upcoming) |
| **Visualization**    | Wordclouds, Plots, Dashboard (upcoming)                       |
| **Deployment**       | Flask Web App (upcoming)                                      |
| **Tools**            | Python, spaCy, NLTK, Pandas, scikit-learn                     |

This project reflects a **complete AIML workflow**, from raw data to intelligent insights.

---

# 📂 **Repository Structure**

```
📦 budgetsense-ai/
 ┣ 📄 Budget_Speech.pdf                     → Source budget document
 ┣ 📄 structured_budget_text.csv            → Cleaned dataset (NLP output)
 ┣ 🧠 NLPModule.ipynb                       → Completed text analysis module
 ┣ 💬 SentimentModule.ipynb                 → Upcoming
 ┣ 🔮 ForecastingModule.ipynb               → Upcoming
 ┣ 🌐 DashboardApp/                         → (Planned web deployment)
 ┣ 🖼 G46_phase_1.pptx                      → Main project PPT (Uploaded)
 ┣ 🖼 NLPModule1.pptx                       → NLP explanation PPT
 ┣ 📂 visualizations/                       → TF-IDF, topic, keyword visuals
 ┣ 📄 README.md                             → Documentation
 ┗ 📄 requirements.txt                      → Dependencies
```

---

# 🚀 **How to Explore the Project**

### 1️⃣ View the Project PPT (Strongly Recommended)

The PPT provides a complete walk-through of:
✔ Introduction
✔ Objectives
✔ Literature survey
✔ Methodology
✔ Block diagram
✔ Work plan
✔ Progress completed
✔ Expected outcomes
✔ References

📄 *Files:*

* **G46_phase_1.pptx**   
* **NLPModule1.pptx**

### 2️⃣ Run the NLP Module

Explore extraction, preprocessing, NER, keywords, topics.

### 3️⃣ Examine structured CSV outputs

See the cleaned economic dataset generated from text.

### 4️⃣ Track upcoming modules

Sentiment → Forecasting → Dashboard → Deployment.

---

# 🎯 **Key Outcomes (from PPT)**

✔ Automated extraction and analysis of budget text
✔ Theme, sector, and keyword intelligence
✔ NER-based policy & allocation detection
✔ Foundation for sentiment analysis
✔ Framework for forecasting future economic trends
✔ Blueprint for an interactive analytics dashboard

Expected final deliverables:

* Full AI-powered budget analysis system
* Sentiment engine
* Forecasting engine
* Interactive dashboard
* Extendable framework for multi-year economic research

---

# 👤 **Author**

**Janhavi Patil**
AI/ML • Data Science • Economic Analytics

---

# 🚧 Project Status

**Work in Progress — More modules will be added soon.**

