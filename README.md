# Customer_Review_Analysis-and-Rating-Prediction-using-NLP
This project demonstrates how Natural Language Processing (NLP) techniques can be combined with a Naive Bayes classifier to analyze customer reviews and predict their ratings. The pipeline is designed to transform raw text into structured features, apply statistical transformations, and classify reviews into rating categories.

🔹 Pipeline Workflow
The pipeline follows a clear, three-step process:

# Feature Extraction & Transformation
- Applied CountVectorizer to convert text into a bag-of-words representation.
- Transformed features using TF-IDF to capture word importance across reviews.

# Classification
- Trained a Naive Bayes classifier (MultinomialNB) on the TF-IDF features.
- Evaluated performance using accuracy, precision, recall, and F1-score.

🔹 Tools & Technologies
- Python
- Libraries:
- NLTK → stopword removal, tokenization
- scikit-learn → CountVectorizer, TF-IDF Transformer, Naive Bayes, evaluation metrics
- pandas & numpy → dataset handling
- matplotlib / seaborn → performance visualization




