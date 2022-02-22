# wordle-solution
This script calculates the best beginning word for the game Wordle, if the solutions are among the top X frequent words on the internet. 

We use the Natural Language Corpus Data derived from the Google Web Trillion Word Corpus to get the top X frequent words. 

We use the Information Entropy formula introduced by Shannon to calculate the entropy each possible begining word can provide, 
and choose the one with the maximum entropy. 
