This approach consists of two components: 

1. **Term Frequency**: Notes the frequency of a word in one document. 
2. **Inverse Document Frequency**: Notes the rareness of a word across all documents and downplays words that occur frequently across all documents. 

In short, TF-IDF is more likely to reduce the importance of a word the more times it appears across all documents. This prevents empty words from accidentally swaying a model, making ==TF-IDF a more focused variation of bag-of-words==


TF-IDF is an example of feature scaling in machine learning models [ibm tf-idf](https://www.ibm.com/think/topics/bag-of-words)
