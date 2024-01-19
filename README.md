# Finanacial_emotion_detection_NLP

I have employed a step-by-step approach, utilizing various methods, to analyze the data:

Initially, I conducted basic data preprocessing. This involved removing punctuation, stop words, end lines, extra spaces, single characters, numbers, and special characters, using Gensim's small model and Python's re library.

1. For preliminary sentiment analysis, I utilized the Afinn tool, which yielded moderate results.

2. I then applied TF-IDF to the data and utilized several non-parametric classifiers, including KNeighborsClassifier, GradientBoostingClassifier, a combination of GradientBoostingClassifier and MultinomialNB, and RandomForestClassifier, as well as a combination of RandomForestClassifier and MultinomialNB.

3. I leveraged SpaCy's extensive English corpus to train embeddings, followed by the application of an LSTM model.

4. I developed a custom tokenization of word embeddings, which were then used in an LSTM model.
   
5. I have pretrained word embeddings using word2vec-google-news-300 and then used those word embeddings in a LSTM model

7. Finally, I trained the data using the FastText model and plan to apply LSTM to these pre-trained word embeddings.








