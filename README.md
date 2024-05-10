
## RNN Implimentation using pytorch for News Article Classification
This project tackles the task of classifying news articles into four categories: World, Sports, Business, and Science/Technology.

## Dataset:
- The dataset NLP3.zip contains training and testing data in CSV format. It includes news texts and their corresponding category labels (World, Sports, Business, Sci/Tech).
- The train dataset contains 2000 sentences, while the test dataset contains 500 sentences. The train dataset is equally distributed, i.e., it has 25% samples from each of the four classes

# Task 1: Word2Vec and RNNs
## Data Preprocessing:
- Clean news texts: Remove punctuation, stop words, and convert text to lowercase.
- Tokenize sentences into words.
- Create a vocabulary of the most frequent words.
- Train a Word2Vec model to learn word embeddings, capturing semantic relationships.
## RNN Model for Classification:
- Represent each sentence as a sequence of word embeddings.
- Build an RNN model  to process the sequence and predict the category.
- Train the RNN model on the training data.
## Evaluation:
- Use a validation set (10% of training data) to monitor model performance during training.
- Evaluate the final model on the unseen test set using metrics like accuracy, precision, recall, and F1-score for each category.
