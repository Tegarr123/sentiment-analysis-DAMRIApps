# 📈 DAMRI Apps Sentiment Analysis
This project focuses on sentiment analysis of user reviews for the **DAMRI Apps mobile application** collected from the Google Play Store. The purpose of this study is to understand user perceptions, highlight recurring issues, and gain insights that can help improve the quality and usability of the application.
<br><img src="images/damri.jpg" width="1280"><br>
## 📂 Project Structure
```bash
sentiment-analysis-DAMRIApps
├── data
│   ├── damri_apps_preprocessed.csv
│   └── damri_apps_raw.csv
└── notebooks
    ├── 01_DAMRI_Apps_Scrapping.ipynb
    ├── 02_DAMRI_Apps_Preprocessing.ipynb
    ├── 03_DAMRI_Apps_RegEx.ipynb
    ├── 04_DAMRI_Apps_BoW.ipynb
    ├── 05_DAMRI_Apps_EDA.ipynb
    └── 06_DAMRI_Apps_TF-IDF.ipynb
```
## 🛠️ Tools and Libraries
- Jupyter Notebook = tool for writing code in python
- ```pandas``` = Library for data manipulation and analysis.
- ```google_play_scraper``` = Library for scrapping app information and user reviews from Google Play Store.
- ```numpy``` = Library for numerical computing in Python.
- ```nltk``` = Library for NLP (Natural Language Processing) toolkit.
- ```matplotlib``` & ```seaborn``` = Library for Data visualization.
- ```re``` = Library for Text processing with regex.
- ```PySastrawi``` = Library for Indonesian language stemming.
- ```scikit-learn``` & ```xgboost``` = Library for machine learning model.
