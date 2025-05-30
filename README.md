# Toxic Comments Detection using Machine Learning for Roman Urdu
This project focuses on detecting toxic comments written in Roman Urdu using machine learning classification models. Three different algorithms—Naive Bayes, Decision Tree, and Random Forest—were applied to classify comments as toxic or non-toxic.

Key Highlights:
Evaluated models based on accuracy, precision, recall, F1-score, and confusion matrices.

Naive Bayes showed decent recall but struggled with many false positives, indicating difficulty in accurately distinguishing non-toxic comments.

Decision Tree achieved the highest accuracy (~99.7%) and balanced precision and recall effectively, making it a strong classifier for this task.

Random Forest offered a good balance between precision and recall, with strong generalization and low false positive rates, providing robustness in detecting toxic content.

Conclusion:
Both Decision Tree and Random Forest models performed exceptionally well for toxic comment detection in Roman Urdu, with Random Forest demonstrating better generalization and robustness. This project showcases practical applications of NLP and machine learning for moderating online content in low-resource languages.

# Toxic Comments Detection using Machine Learning for Roman Urdu

This project uses machine learning to classify Roman Urdu comments as toxic or non-toxic using three models: Naive Bayes, Decision Tree, and Random Forest.

## 📌 Project Highlights

- Preprocessed a Roman Urdu dataset of comments.
- Applied NLP techniques and feature engineering.
- Trained and evaluated ML models: Naive Bayes, Decision Tree, and Random Forest.
- Measured performance using accuracy, precision, recall, F1-score, and confusion matrices.
- Decision Tree and Random Forest performed with high accuracy and generalization.

## 📁 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/kashif7723/Toxic-Comments-Detection-using-Machine-Learning-for-Roman-Urdu.git

2. Open the Jupyter Notebook:
jupyter notebook toxic_comments_detection.ipynb

3. Run all cells to preprocess data, train models, and view evaluation metrics.

4.  Google API Setup (Optional - For YouTube Comments)
To fetch Roman Urdu comments directly from YouTube using the YouTube Data API:

  4.1  Go to the Google Cloud Console and create a new project.

  4.2  Enable YouTube Data API v3.

  4.3  Generate an API key and paste it into the notebook

  4.4  Use the API to extract comments from YouTube videos for analysis.

⚠️ Do not commit or share your API key publicly.

🚀 Future Improvements
Expand the dataset with more labeled Roman Urdu data.

Integrate deep learning models (e.g., LSTM, BERT).

Deploy as a web app using Streamlit or Flask.
