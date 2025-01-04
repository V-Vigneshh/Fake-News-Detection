# Fake News Detection Project

This project aims to detect fake news articles using machine learning techniques. The goal is to help combat the spread of misinformation by identifying whether a given news article is credible or fake.

## Dataset
The dataset used for this project is `fakenewsnet.csv`, which includes labeled news articles with features such as title, text, and class labels (e.g., Fake or Real).

## Features
- **Machine Learning Models Used:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest Classifier
  - Decision Tree Classifier
- **Evaluation Metrics:** Accuracy, Precision, Recall, and F1 Score were used to evaluate model performance.
- **Preprocessing Steps:**
  - Data cleaning (removal of special characters, stop words, etc.)
  - Text vectorization using techniques like TF-IDF

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
   ```
2. Install the required libraries manually if needed (e.g., `pandas`, `sklearn`, `numpy`).

## Running the Project

1. Ensure the dataset `fakenewsnet.csv` is in the same directory as the code.
2. Run the code:
   ```bash
   python fakenews_detection.py
   ```
3. The script will:
   - Preprocess the dataset
   - Train and evaluate all models
   - Print the evaluation metrics in the console

## Results
- The **Support Vector Machine (SVM)** provided the best results with a high accuracy and balanced precision-recall.

## Future Improvements
- Incorporate deep learning models such as LSTMs or transformers for improved accuracy.
- Experiment with additional datasets to enhance generalizability.
- Develop a web interface for real-time news verification.

## Folder Structure
```
.
├── fakenewsnet.csv
├── fakenews_detection.py
└── README.md
```
