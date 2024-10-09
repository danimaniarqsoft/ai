#overfitting

> [!NOTE] Overfitting
> Creating a model that matches the training data so closely that the model fails to make correct predictions on new data.

Regularization can reduce overfitting. Training on a large and diverse training set can also reduce overfitting.
## Why does overfitting occur?

- The training data size is too small and does not contain enough data samples to accurately represent all possible input data values.  
- The training data contains large amounts of irrelevant information, called noisy data.  
- The model trains for too long on a single sample set of data.  
- The model complexity is high, so it learns the noise within the training data.
## How can you detect overfitting?


Training data and Testing data
Other considerations:
- Avoid overfitting and data snooping bias with test data
- Create a Test data set with just pick some instances randomly, tipically 20% of the dataset, and set them aside. The other 80% is named training data set 



References
1. https://aws.amazon.com/what-is/overfitting/
2. 