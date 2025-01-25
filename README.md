# Fake-News-Detection

- **Project Objective**: Developed a machine learning model to classify news articles as "fake" or "real" using a combination of the Naïve Bayes classifier and a Bi-directional Long Short-Term Memory (Bi-LSTM) Recurrent Neural Network (RNN).

- **Algorithms Utilized**:
  - **Naïve Bayes Classifier**: Applied the Naïve Bayes algorithm to model the probability distribution of words and features in the articles. This probabilistic classifier helped capture the basic associations between keywords and their likelihood of indicating fake or real news.
  - **Bi-directional LSTM (RNN)**: Incorporated Bi-LSTM, a deep learning model that processes text in both forward and backward directions. This enables the network to capture context from both preceding and succeeding words in a sentence, improving the understanding of complex sentence structures and semantics.

- **Text Preprocessing**: Performed extensive text preprocessing steps, including tokenization, stop-word removal, stemming, and vectorization (using techniques like TF-IDF or Word2Vec) to convert news articles into structured formats suitable for model training.

- **Model Training & Validation**: Trained both models on a labeled dataset of news articles, evaluating performance through techniques such as cross-validation, hyperparameter tuning, and loss function optimization to maximize classification accuracy.

- **Evaluation Metrics**: Measured the model’s performance using metrics such as accuracy, precision, recall, F1-score, and AUC, ensuring the system's robustness in distinguishing fake news from real news.

- **Deployment**: Deployed the model in a real-time news classification system capable of flagging potentially fake news articles based on their content, assisting in media verification and content moderation.

- **Applications**: Ideal for news platforms, social media networks, and content moderation systems to reduce the spread of misinformation and enhance news credibility.
