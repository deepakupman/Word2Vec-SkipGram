# Word2Vec-SkipGram
Word2Vec algorithm implementation using Skipgram in PyTorch. [Dataset](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)

**Word2Vec** algorithm can be implemented in two ways **CBOW** and **Skip-Gram**. [image](./word2vec_architectures.png)

**SkipGram:**
```
Given a set of sentences the model loops on the words of each sentence and either tries to use the 
current word of to predict its neighbors (its context), in which case the method is called “Skip-Gram”.
```
**CBOW:** 
```
It uses each of these contexts to predict the current word, in which case the method is called 
Continuous Bag Of Words (CBOW). 
The limit on the number of words in each context is determined by a parameter called “window size”.
```
