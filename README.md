# Statistical_language_modelling
Exploring some simple statistical models of English text. Project completed as part of homework 4 of CSE 250A of UCSD, CSE, Fall 2022. 

# Brief Description: 
Based on the maximum likelihood estimation technique, we create a simple statistical model of the English text. We calculate maximum likelihood estimates of the unigram and the bigram distributions, log-likelihoods of sentences under unigram, bigram, and mixture models. 

For a detailed description of the model and tasks in this project, please refer to the file 'Problem Statement.pdf'

# Files : 
1. hw4_readme.txt: text file with the information about the data files.
2. hw4_vocab.txt: Contains a list of 500 tokens, corresponding to words, punctuation symbols, and other textual markers.
3. hw4_unigram.txt: Contains the counts of each of these tokens in a large text corpus of Wall Street Journal articles.  The corpus consisted of roughly 3 million sentences.
4. hw4_bigram.txt:  Contains the counts of pairs of adjacent words in this same corpus.  Let count(w1,w2) denote the number of times that word w1 is followed by word w2.  The counts are stored in a simple three-column format:   index(w1)  index(w2)  count(w1,w2). 
5. Problem Statement.pdf: The detailed problem statement with each part indicated.
6. code.ipynb: The code to solve the problem parts as given in 'Problem Statement.pdf'. 

# Execution :
Execute code.ipynb notebook according to parts. You may have to run the previous part's code before going to the next part. 

