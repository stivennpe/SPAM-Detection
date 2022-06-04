# SPAM-Detection
Spam detection implementation

Two implementations of a Spam detector in Keras:

1. LSTM SPAM:
- Unidirectional LSTM 
- Randomly Initiallized embeddings
- Dense(500, activation='relu') 

2. Bi-LSTM SPAM:
- Bidirectional LSTM 
- Dense(128, activation='relu')
- Dense(1, activation='sigmoid')
- Glove  (glove.6B.100d.txt) embeddings

Dataset not provided due to confidentiality issues.
