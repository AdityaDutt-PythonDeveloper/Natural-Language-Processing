NLP is very helpful in Text preprocessing. It help machine to understand and generate human language , both spoken and written. 
There are various steps involved in NLP and these are :
  a. text to lowercase
  b. Removing stopwords
  c. Tokenization
  d. Stemming
  e. Regular Expression
  f. N-grams
  g. Lemmatization

All these are part of text preproccsing so that it would be easy for a LLM to understand Human language. 
All these steps are done seperately as examples and also collectively done on a csv file

Parts of Speech tagging :
Labeling each word in a sentence with a grammetical role.
To use POS in python we use spacy library in python.
spacy : In NLP library that comes with pretrained model capable of recognizing POS, named entities, and other lingustic features.

A spacy document an object that stores the test along with all the lingustic information spacy generates.
It takes text as and input and turns it into structered document where each word is already tokenized and tagged.
