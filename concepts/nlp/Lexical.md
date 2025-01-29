**other names**: tokenizer

Interpret the meaning of individual words

Sundry types of processing bestow to word-level understanding – the first of these being a part-of-speech tag to each word. In this processing,

words that can act as more than one partof-speech are assigned the most probable part-of-speech tag based on the context in which they occur.

At the lexical level, Semantic representations can be replaced by the words that have one meaning. 

Lexical level, analysis of structure of words is performed with respect to their lexical meaning and PoS. 

In this analysis, text is divided into **paragraphs**, **sentences**, and **words**. 
1. Words that can be associated with more than one PoS are aligned with the most likely PoS tag based on the context in which they occur. 
2. At lexical level, semantic representation can also be replaced by assigning the correct POS tag which improves the understanding of the intended meaning of a sentence. 
3. It is used for cleaning and feature extraction using various techniques such as **removal of stop words**, **stemming**, **lemmatization** etc. 

**Stop words** such as ‘in’, ‘the’, ‘and’ etc. are removed as they don’t contribute to any meaningful interpretation and their frequency is also high which may affect the computation time. 

**Stemming** is used to stem the words of the text by removing the suffix of a word to obtain its root form. For example: consulting and consultant words are converted to the word consult after stemming, using word gets converted to us and driver is reduced to driv. 

**Lemmatization** does not remove the suffix of a word; in fact, it results in the source word with the use of a vocabulary. For example, in case of token drived, stemming results in “driv”, whereas lemmatization attempts to return the correct basic form either drive or drived depending on the context it is used.