In this repository are kept all of the NLP Projects and files


## Project 1
The aim of this project was to reproduce some experiments presented in the Mathematical Theory of
Communication by Claude Shannon, 1948. 
The paper can be found at: https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf


Tasks covered in this project are:
1. Implementatio of a character sequence generator with uniform probability distribution
2.  Implementation of a character sequence generator with character probability distribution from
English text
3.  Implementation of an n-gram language model that can be trained on some English data
4. Training the model on the provided text: The Adventures of Sherlock Holmes, obtained from
the Project Gutenberg [https://www.gutenberg.org/]
5.  Implementation of a text generator that samples word from the model given a specific prefix.
## Project 2
The aim of this project was to classify Consumer Finance Complaints into one of the 17 pre-defined classes. This is a multi-class text classification problem. 

Tasks covered in this project are:
1. Data Exploration
From the dataset only two columns are needed — “Product” and “Consumer complaint narrative”.

__Input: Consumer_complaint_narrative__
Example: “ I have outdated information on my credit report that I have previously disputed
that has yet to be removed this information is more then seven years old and does not meet credit
reporting requirements”

__Output: product__
Example: Credit reporting We will remove missing values in the “Consumer complaints narrative” column, and add a column encoding the product as an integer because categorical variables
are often better represented by integers than strings.
2. Imbalanced Classes Problem
3. Text Representation(Bag of Words, TF-IDF)
4. Training the Logistic Regression model
5. Model Evaluation(confusion matrix and missclassified cases exploration)


## Project 3
In a Hidden Markov Model (HMM), there is an invisible Markov chain (which cannot be observed), and each state generates in random one out of observations, which are visible.
The Markov Chain considered in this project comes with three states (snow, rain and sunshine), - the transition probability matrix and — the initial probabilities. The weather cannot be directly observed but the temperature inside the room can leading to observations: cold or hot. 

Tasks covered in this project are:
1. Hidden Markov Model
2. Finding Hidden States - Viterbi Algorithm






## Project 4

The aim of this project is to implement a machine learning model based on Naive Bayes for a
sentiment analysis task using the Rotten Tomatoes movie review dataset. Obstacles like sentence
negation, sarcasm, terseness, language ambiguity, and many others make this task very
challenging.

The dataset is a corpus of movie reviews originally collected by Pang and Lee. This dataset
contains tab-separated files with phrases from the Rotten Tomatoes dataset. The data are split
into train/dev/test sets and the sentences are shuffled from their original order.
• Each sentence has a SentenceId.
• They all have been tokenized already.
The training, dev and test set contain respectively 7529, 1000 and 3310 sentences. The sentences
are labelled on a scale of five values:
0. negative
1. somewhat negative
2. neutral
3. somewhat positive
4. positive


This project includes the report summing up the whole results section.


Some of these projects were a partial requirement for the COM4513 Natural Language Processing, COM3110 Text Processing as either assignments or labs at The University of Sheffield.

**Requirements:**
1. to run the projects please make sure to install nltk and other necessary libraries such as numpy, matplotlib, pandas and sklearn.