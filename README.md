### 📌 Project Overview
This project focuses on detecting fake news using machine learning, specifically the Naïve Bayes classifier. Fake news spreads rapidly on social media and can negatively impact public discourse. The goal is to build an efficient fake news detection model that can differentiate between real and fake news articles.

🗂️ Dataset
Source: The dataset is sourced from Kaggle ("Fake and Real News" dataset).
Size:
Fake news articles: ~23,000 samples
Real news articles: ~20,000 samples
Features:
Title
Text content
Labels (Fake/Real)
🔧 Methodology
Data Preprocessing
Handling missing values
Encoding categorical variables
Feature scaling
Model Development
Training using Naïve Bayes
Hyperparameter tuning (Grid Search/Random Search)
Evaluation Metrics
Accuracy: Measures overall correctness
Precision: Ensures fewer false positives
Recall: Identifies real fake news instances
F1-score: Balance between precision and recall
📊 Results
Algorithm	Accuracy	Strengths	Weaknesses
Naïve Bayes (Proposed)	98%	Fast, efficient, simple	Struggles with contextual understanding
LSTM (Deep Learning)	92%	Captures sequence dependencies	Computationally expensive
Random Forest	95%	Handles large datasets	Slower than Naïve Bayes
SVM	93%	Effective for small datasets	High complexity
🚀 Future Enhancements
Integrating deep learning models (LSTM, transformers) for better contextual understanding.
Expanding the dataset to support multiple languages.
Developing a real-time browser extension for fake news detection.
Improving the user interface for accessibility.
🛠️ Tech Stack
Programming Language: Python
Libraries Used: Pandas, NumPy, Scikit-learn, Matplotlib
Development Environment: Google Colab
📜 References
Various research papers and machine learning methodologies have been explored. See the project report for a detailed literature review.
