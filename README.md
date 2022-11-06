# NLP_Text_Analysis
This is a NLP based Text preprocessing model developed to take care of the major preprocessing which needs to be done for language processing.<br />

The major tasks performed by the model is to recognise:<br />
1. Parts of Speech <br />

What is the meaning of a particular part of the sentence like whether it is a noun , pronoun or adjective.<br />
The basic abbrevations used by scikit learn are as follows:<br />

##Part of Speech<br />

NNS → Noun Plural ie.Tables <br />
NN → Noun Singular ie.Table<br />
VBG → Verb<br />
PRP → Pronoun<br />

2. Named Entity Recognition.<br />

To get awareness about the type of named entitiy used in the input text, NER is performed on the input data to gate a brief idea about what is the basic conclusion out of thr text.<br />
I have used Spacy,  a module offered by python for fast and accurate recognitions of the named entity.<br />
The abbrevations used by them are as follows:<br />

##Named Entity Realtions<br />

PERSON:      People, including fictional.<br />
NORP:        Nationalities or religious or political groups.<br />
FAC:         Buildings, airports, highways, bridges, etc.<br />
ORG:         Companies, agencies, institutions, etc.<br />
GPE:         Countries, cities, states.<br />
LOC:         Non-GPE locations, mountain ranges, bodies of water.<br />
PRODUCT:     Objects, vehicles, foods, etc. (Not services.)<br />
EVENT:       Named hurricanes, battles, wars, sports events, etc.<br />
WORK_OF_ART: Titles of books, songs, etc.<br />
LAW:         Named documents made into laws.<br />
LANGUAGE:    Any named language.<br />
DATE:        Absolute or relative dates or periods.<br />
TIME:        Times smaller than a day.<br />
PERCENT:     Percentage, including ”%“.<br />
MONEY:       Monetary values, including unit.<br />
QUANTITY:    Measurements, as of weight or distance.<br />
ORDINAL:     “first”, “second”, etc.<br />
CARDINAL:    Numerals that do not fall under another type.<br />


3. Sentiment Analysis <br />

After all the preprocessing is done we need to analyse the context of the sentence entered hat whether it is a positive or negative sentence. <br />
Kaggle's dataset is used for mode traininig after all the preprocessing is done ( tokenization,Stopwords removal, stemming, vectorization (Counter)).<br />
Naive Bayes model is used for classification of the data as positive or negative after analysing it on various fronts.<br />
Bernoulli Naive Bayes model is used for classification.<br />
Count Vectorization is used to transform the data to pass onto the model.<br />

0 - Negative <br />
1 - Positive<br />

![image](https://user-images.githubusercontent.com/62856191/200178158-ab69c480-712d-44dd-9cb9-34371730a418.png)

##Functioning of the model:<br />

![image](https://user-images.githubusercontent.com/62856191/200178197-7b3e86f5-d16d-4365-9ec4-26b5b4776a4e.png)
<br />
<br />
![image](https://user-images.githubusercontent.com/62856191/200178180-18c769f7-3787-41ac-aea3-c59a7112f64c.png)
<br />
<br />
![image](https://user-images.githubusercontent.com/62856191/200178214-f87b0fa1-47ea-4700-9dee-13a074149e45.png)
<br />
<br />

Modules Used:<br />
1. NumPy<br />
2. Pandas<br />
3. nltk<br />
4. SkLearn<br />

  *stopwords <br />
  *word_tokenize <br />
  *Count_Vectorization <br />
  *Confusion Matrix <br />
  *PortStemmer <br />
