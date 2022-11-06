# NLP_Text_Analysis
This is a NLP based Text preprocessing model developed to take care of the major preprocessing which needs to be done for language processing.

The major tasks performed by the model is to recognise:
1. Parts of Speech 

What is the meaning of a particular part of the sentence like whether it is a noun , pronoun or adjective.
The basic abbrevations used by scikit learn are as follows:
!Part of Speech!
# NNS → Noun Plural ie.Tables
# NN → Noun Singular ie.Table
# VBG → Verb
# PRP → Pronoun

2. Named Entity Recognition.

To get awareness about the type of named entitiy used in the input text, NER is performed on the input data to gate a brief idea about what is the basic conclusion out of thr text.
I have used Spacy,  a module offered by python for fast and accurate recognitions of the named entity.
The abbrevations used by them are as follows:

!Named Entity Realtions!
# PERSON:      People, including fictional.
# NORP:        Nationalities or religious or political groups.
# FAC:         Buildings, airports, highways, bridges, etc.
# ORG:         Companies, agencies, institutions, etc.
# GPE:         Countries, cities, states.
# LOC:         Non-GPE locations, mountain ranges, bodies of water.
# PRODUCT:     Objects, vehicles, foods, etc. (Not services.)
# EVENT:       Named hurricanes, battles, wars, sports events, etc.
# WORK_OF_ART: Titles of books, songs, etc.
# LAW:         Named documents made into laws.
# LANGUAGE:    Any named language.
# DATE:        Absolute or relative dates or periods.
# TIME:        Times smaller than a day.
# PERCENT:     Percentage, including ”%“.
# MONEY:       Monetary values, including unit.
# QUANTITY:    Measurements, as of weight or distance.
# ORDINAL:     “first”, “second”, etc.
# CARDINAL:    Numerals that do not fall under another type.

3. Sentiment Analysis

After all the preprocessing is done we need to analyse the context of the sentence entered hat whether it is a positive or negative sentence.
Kaggle's dataset is used for mode traininig after all the preprocessing is done ( tokenization,Stopwords removal, stemming, vectorization (Counter)).
Naive Bayes model is used for classification of the data as positive or negative after analysing it on various fronts.
Bernoulli Naive Bayes model is used for classification.
Count Vectorization is used to transform the data to pass onto the model.

0 - Negative 
1 - Positive

![image](https://user-images.githubusercontent.com/62856191/200178158-ab69c480-712d-44dd-9cb9-34371730a418.png)

Functioning of the model:
![image](https://user-images.githubusercontent.com/62856191/200178197-7b3e86f5-d16d-4365-9ec4-26b5b4776a4e.png)
![image](https://user-images.githubusercontent.com/62856191/200178180-18c769f7-3787-41ac-aea3-c59a7112f64c.png)
![image](https://user-images.githubusercontent.com/62856191/200178214-f87b0fa1-47ea-4700-9dee-13a074149e45.png)

Modules Used:
1. NumPy
2. Pandas
3. nltk
4. SkLearn
  *stopwords
  *word_tokenize
  *Count_Vectorization
  *Confusion Matrix
  *PortStemmer
