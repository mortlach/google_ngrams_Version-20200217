# Method For 1-grams
## get all 1 grams converted to lower case 
## choose those with:
### no part with postag = \_NOUN,\_VERB,\_ADJ,\_ADV,\_PRON,\_DET,\_ADP,\_NUM,\_CONJ,\_PRT,\_ROOT,\_START,\_END,\_.,\_X  
### less than 15 runes 
### apostrophe words with rune lengths 2'1 and 3'1
### words in cicadawords dictionary
### words in wolfram english dictionary
### words in scrabble dictionary 
### words in nltk.corpus.brown.words() dictionary
### words in nltk.corpus.inaugural.words() dictionary
### words in nltk.corpus.words.words() dictionary