# Sentiment Analysis Using Machine Learning

## Project Overview
This project uses Machine Learning and Natural Language Processing
to classify text into three sentiment categories:
- Positive
- Negative
- Neutral

## Objective
To build a sentiment classification system that understands
textual input and predicts the sentiment expressed by the user.

## Dataset
- Training samples: 31,193
- Testing samples: 5,199
- Classes: Positive, Negative, Neutral

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- TF-IDF

## Data Preprocessing
- Converted text to lowercase
- Removed URLs and usernames
- Removed special characters and punctuation
- Removed empty sentences

## Machine Learning Algorithms
1. Logistic Regression
2. Multinomial Naive Bayes
3. Linear Support Vector Machine (SVM)

## Model Performance

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 67.38% |
| Multinomial Naive Bayes | 62.74% |
| Linear SVM | 66.07% |

## Hyperparameter Tuning
GridSearchCV with 3-fold cross-validation was used.
Best parameter: C = 1

## Final Model
Logistic Regression

Test Accuracy: 67.38%

## Saved Model Files
- sentiment_model.pkl
- tfidf_vectorizer.pkl

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   pip install -r requirements.txt

3. Open Sentiment_Analysis.ipynb in Jupyter Notebook.
4. Run the notebook cells sequentially.

## Future Improvements
- Improve model accuracy
- Experiment with advanced NLP techniques
- Build a web interface using Flask
- Support multiple languages

## Author
Divya
