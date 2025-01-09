# NLP-Sentiment-Analysis-Project

## Project Overview
This project focuses on performing sentiment analysis on Baldur's Gate 3 Steam reviews. Using machine learning and deep learning models, we classify reviews as positive or negative based on user feedback. The project involves preprocessing, feature extraction, exploratory data analysis, and training/testing multiple models to evaluate their effectiveness.

## Repository Structure
- **`/data/`**:
  - `BG3_reviews_resampled.csv`: Preprocessed and balanced dataset used for training and evaluation.
- **`/docs/`**:
  - `report.pdf`: The detailed project report, including methodology, results, and analysis.
- **`/notebooks/`**:
  - `ml_model_training.ipynb`: Notebook for training machine learning models.
  - `dl_model_training.ipynb`: Notebook for training deep learning models.
- **`/results/`**:
  - **`confusion_matrices/`**: Contains confusion matrix visualizations for each model.
  - **`reviews_length_distributions/`**: Distribution plots of review lengths for different data forms.
  - **`roc_curves/`**: ROC curve plots for each model.
  - **`training_history_visualizations_for_dl/`**: Visualizations of training history (accuracy and loss) for deep learning models.
  - **`word_clouds/`**: Word clouds for positive and negative reviews.
  - `evaluation_metrics.csv`: Consolidated evaluation metrics for all models.

## Dataset
The dataset includes Baldur's Gate 3 reviews scraped from Steam. Reviews are labeled as positive or negative based on user recommendations. The dataset was preprocessed and resampled to address class imbalance.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/NLP-Sentiment-Analysis-Project.git
   cd NLP-Sentiment-Analysis-Project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebooks:
   - Use `ml_model_training.ipynb` for machine learning models.
   - Use `dl_model_training.ipynb` for deep learning models.

## Results
- **Best-Performing Model**: SVM with TF-IDF features
  - **Accuracy**: 90%
  - **AUC-ROC**: 0.97
- **Deep Learning Performance**: CNN showed comparable results with faster training times.
- Visualizations and metrics can be found in the `/results/` folder:
  - Confusion matrices, ROC curves, and evaluation metrics for all models.

## Report
For a detailed explanation of the methodology, results, and insights, refer to the [project report](docs/report.pdf).

## Future Work
- Explore advanced deep learning models like BERT.
- Perform hyperparameter tuning for machine learning models.
- Expand the dataset with reviews from other platforms.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or feedback, please contact:
- **Author**: Nikolaos Theokritos Tsopanidis
- **Email**: nikos.tsopanidis746@gmail.com
