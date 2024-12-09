# NLP-Sentiment-Analysis-Project
Here I upload all the files relevant to my sentiment analysis project.
- **Kaggle link:** https://www.kaggle.com/code/nicktsopanidis/webex-reviews-scraping

The `Google_play_store_scraping` notebook is an edited version of https://www.kaggle.com/code/ashishkumarak/google-play-reviews-scraping-daily-update?kernelSessionId=205779104.

# WebEx Sentiment Analysis

## Description
This project focuses on performing sentiment analysis on Google Play Store reviews for the WebEx application. Using machine learning models, we classify reviews into positive or negative sentiments. The workflow involves data scraping, preprocessing, exploratory data analysis (EDA), and training/testing various machine learning models.

## Project Overview
- **Data Scraping**: Google Play API was used to scrape WebEx reviews.
- **Preprocessing**: Reviews were cleaned and prepared for analysis.
- **Exploratory Data Analysis (EDA)**: Insights into review distribution, word frequencies, and sentiment trends.
- **Machine Learning Models**: Logistic Regression, SVM, and Random Forest were trained to predict sentiment.

## Repository Structure
- **`webex_sentiment_analysis.ipynb`**: Main Jupyter notebook with the entire workflow.
- **`webex_reviews.csv`**: Scraped and cleaned dataset of WebEx reviews.
- **`data_scraper.py`**: Python script for scraping reviews from Google Play.
- **`data_preprocessing.py`**: Script for data cleaning and preprocessing.
- **Model Scripts**:
  - `logistic_regression_model.py`
  - `svm_model.py`
  - `random_forest_model.py`
- **`results/`**: Folder containing graphs, metrics, and visualizations.
- **`requirements.txt`**: List of Python dependencies.

## Dataset
The dataset consists of reviews scraped from the Google Play Store for the WebEx application. Each review is labeled with its sentiment (positive/negative).

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/WebEx-Sentiment-Analysis.git
   cd WebEx-Sentiment-Analysis

2. Install dependencies:

pip install -r requirements.txt


3. Run the Jupyter notebook:

jupyter notebook webex_sentiment_analysis.ipynb



Results

Sentiment classification accuracy: [Insert accuracy metric]

Visualizations of word clouds, confusion matrices, and sentiment distributions are available in the results/ folder.


Challenges and Future Work

Challenges include handling noisy data and achieving better accuracy for complex reviews.

Future work involves experimenting with deep learning techniques like LSTMs or BERT for improved results.


License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For any inquiries or feedback, feel free to contact me at [nikos.tsopanidis746@gmail.com].
