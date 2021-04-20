# Natural-Language-Processing
 
1) Regular Expressions
2) Text Preprocessing
3) Parts of Speech tagging

Parts of Speech Tagging
Part of speech(POS) of a word is its grammatical property like noun, pronoun, verb, adjective etc. 
POS tagging is assigning words in a corpus with their respective parts of speech. 
The pos_tagger.ipynb notebook shows example of how to pos tag for custom corpus through nltk.

Unigram - Most frequent tag for the word in training corpus.
Bigram - It uses a tuple consisting of the token’s base type and the tags of the 1(n-1) preceding tokens.
Trigram - It uses a tuple consisting of the token’s base type and the tags of the 2 preceding tokens. 
It then picks the tag which is most likely for that context. 
The bi/trigram does not support unknown words on its own it is backed off with (n-1)gram.
HMM - Unobservable states are pos tags and observable ouputs are words.
