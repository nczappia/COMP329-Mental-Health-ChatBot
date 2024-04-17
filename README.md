# COMP329-Mental-Health-ChatBot
## Outline
We will be testing building a ChatBot using transfer learning from LLMs, Seq2Seq models, and potentially a neural network from scratch.
## Goal
Our goal is to optimize the model for performing the role of being a therapist/mental health expert that can converse with people looking for help or information regarding mental health.
## Details
### Dataset 
Emotions Dataset
* Already Preprocessed (lowercase, no special characters)
* Text as features, 6 emotions as labels

### Embeddings
Word2Vec/TF-IDF
* Using the Google News Model's Word2Vec Embeddings
* Using sklearn's TFIDF Vectorizer and training on the Emotions Dataset

### Model
RNN
* Using SimpleRNN from keras

### Dataset
https://www.kaggle.com/datasets/bhavikjikadara/emotions-dataset
