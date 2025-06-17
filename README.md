# Charlotte Parks Sentiment Analysis

**A community-driven data project using natural language processing to uncover how Charlotte residents perceive local parks.**

## 📌 Project Overview

This project uses sentiment analysis to evaluate over 3,000 public Google Maps reviews from 16 Charlotte-Mecklenburg parks. The goal is to identify common factors driving positive or negative sentiment and make actionable recommendations to local policymakers and urban planners.

## 🛠 Tools & Technologies
- **Python**: NLTK, TextBlob, Pandas, Matplotlib, Scikit-learn
- **NLP Techniques**: TF-IDF, chi-square feature selection, polarity scoring
- **Visualization**: Bar charts, bigrams, and sentiment maps
- **Data Source**: Google Maps public reviews

## 🔍 Key Methods
- **Text Preprocessing**: Tokenization, stopword removal, spelling correction
- **Sentiment Scoring**: Using TextBlob's polarity scale (-1 to 1)
- **Classification**: Support Vector Classifier (SVC) for polarity categorization
- **Feature Extraction**: TF-IDF and n-gram analysis to identify recurring themes
- **Zip Code Mapping**: Geo-based clustering of sentiment trends

## 📊 Results Summary
- 70% of reviews were positive, 25% neutral, and 5% negative
- Most praised features: disc golf courses, playgrounds, walking trails
- Common issues: noise pollution, safety concerns, homelessness, poor lighting
- ZIP code 28217 was flagged as a priority area for improvement due to sentiment imbalance

## 📈 Recommendations
- Expand kid-friendly amenities like splash pads and playgrounds
- Enhance park lighting and security presence
- Address noise pollution using green buffers (trees, landscaping)
- Invest in high-traffic areas with lower sentiment (e.g., parks near Uptown)

## 📂 Repository Contents
| Folder/File        | Description                                  |
|--------------------|----------------------------------------------|
| `notebooks/`       | Jupyter notebook containing full analysis    |
| `data/`            | Placeholder for raw or cleaned datasets      |
| `visuals/`         | Word clouds, zip code maps, or charts        |
| `README.md`        | Project documentation                        |
| `requirements.txt` | Python packages used                         |

## 📬 Contact
Samuel Fairley — [scfairle@charlotte.edu](mailto:scfairle@charlotte.edu)

---

*This project was developed as part of an undergraduate capstone in Data Science at UNC Charlotte.*
