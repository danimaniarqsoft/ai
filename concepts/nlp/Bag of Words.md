The bag-of-words model is a simple way to represent a document in numerical form before we can feed it into a machine learning algorithm

The-bag-of-words model is a simple way to convert words to numerical representation by conceptualizing a document as a “bag” of words and noting the frequency of each word. Documents can then be embedded and fed into machine learning algorithms.

A key issue with bag-of-words is that simply tracking the frequency of words can lead to meaningless words — words like “a,” “some” and “the” — gaining too much influence over a model. That’s where Term Frequency-Inverse Document Frequency ([[TF-IDF]]) comes into play.

if we no clean data properly we can processing or sparsing errors, so we must to ignore the quotes.

 Model sparsity results in high dimensionality, which, in turn leads to [overfitting](https://www.ibm.com/topics/overfitting) on training data.

Alternatives:

**Bag of n-grams.** 

Adopting n-grams rather than words can correct for a number disadvantages inherent to bag of words models