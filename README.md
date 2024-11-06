# NLP_StopWordandLemmatizationFromTextInput
A text processing script that tokenizes input, removes stop words, and lemmatizes words to generate a clean, simplified word list.

This code processes user input by tokenizing text, removing stop words, and lemmatizing words to produce a cleaned and simplified word list.
1. Setup and Initialization: Imports NLTK libraries for tokenization, stop words, and lemmatization. Downloads necessary NLTK resources (punkt, stopwords, wordnet).
2. Text Input and Tokenization: Takes user text input. Tokenizes the text into individual words.
3. Stop Word Removal: Defines a set of English stop words and filters them out from the word tokens.
4. Lemmatization: Initializes a lemmatizer and applies it to each filtered word, converting words to their base forms.
Output: Displays the list of filtered words (without stop words). Shows the list of lemmatized words for the cleaned text.
This program is useful for preparing text for natural language processing by focusing on essential words and standardizing them to their root forms.
