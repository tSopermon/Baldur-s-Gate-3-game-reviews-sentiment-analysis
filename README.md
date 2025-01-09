# Baldur's Gate 3 Sentiment Analysis

## Description
This project analyzes 309,103 English reviews of **Baldur's Gate 3** from Steam to classify sentiments as positive or negative. Using Machine Learning (ML) and Deep Learning (DL) models, we uncover insights into user feedback about the game.

## Project Overview
- **Dataset**: Reviews were collected via Steam's API, focusing on "review" and "voted_up" columns.
- **Preprocessing**: Data was cleaned, tokenized, lemmatized, and prepared for analysis.
- **Feature Extraction**: Bag of Words and TF-IDF methods were used.
- **Models**:
  - Machine Learning: Logistic Regression, SGD Classifier, Multinomial Naïve Bayes.
  - Deep Learning: Simple RNN, LSTM, CNN.
- **Evaluation**: Models were compared based on accuracy, F1 score, AUC-ROC, and computational efficiency.

## Repository Structure
- **`data/`**: Contains raw and cleaned datasets.
- **`notebooks/`**: Jupyter notebooks for preprocessing, EDA, and model training.
- **`scripts/`**: Python scripts for automating tasks like scraping, preprocessing, and model training.
- **`results/`**: Metrics, visualizations, and analysis results.
- **`requirements.txt`**: Dependencies for running the project.
- **`LICENSE`**: Licensing information.

## Dataset
The dataset was sourced from the [Baldur's Gate 3 Steam Reviews Kaggle dataset](https://www.kaggle.com/datasets/harisyafie/baldurs-gate-3-steam-reviews). Reviews include user feedback, recommendation status, and metadata.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/BG3_Sentiment_Analysis.git
   cd BG3_Sentiment_Analysis
2. Install dependencies:
  ```bash
   pip install -r requirements.txt
  ```
3. Run Jupyter notebooks:
  - Start with `notebooks/preprocessing.ipynb` to clean the data.
  - Use `notebooks/eda.ipynb` for exploratory data analysis.
  - Train ML models using `notebooks/ml_model_training.ipynb`.
  - Train DL models using `notebooks/dl_model_training.ipynb`.

## Results
- **Top-performing model**: SGD Classifier (accuracy: 90%, AUC-ROC: 0.97).
- **Deep learning**: CNN performed best (accuracy: 90%, AUC-ROC: 0.94).
- **Visualizations**: Word clouds, confusion matrices, and ROC curves available in `results/`.

## Future Work
- Optimize ML models with hyperparameter tuning.
- Experiment with pretrained models like BERT for improved accuracy.
- Address overfitting in DL models by increasing dataset size and regularization.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For inquiries, contact: [nikos.tsopanidis746@gmail.com].
