# Topic: Working with Text Data.

## Introduction to NLP
Machine Learning models cannot understand raw text; it must be converted into numbers (vectors).

## 1. Text Preprocessing
- Tokenization: Breaking sentences into individual words (tokens).

- Stop-word Removal: Removing common words like "the", "is", "at" which don't add much meaning.

- Stemming/Lemmatization: Reducing words to their root form (e.g., "running" becomes "run").

## 2. Vectorization Techniques
- Bag of Words (BoW): Counting the frequency of each word.

- TF-IDF (Term Frequency-Inverse Document Frequency): Weights words higher if they are frequent in a document but rare across the entire dataset (helps identify "unique" keywords).

- Word Embeddings: (e.g., Word2Vec) Mapping words to dense vectors where similar words are mathematically close to each other.