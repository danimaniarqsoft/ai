## Other names
- Logistic function
## Graph

## Definition

Is a function bounded between 0 and 1. It will become 0 for values which are very negative and 1 for values which are very positive.
## Use cases

- To ensure values aren’t extremely high or low. 
- This function is usually used at the last layer when we need values which are binary (0 or 1).
- Provide binary output, making it suitable for problems where you want to make a clear distinction between two classes or states
- It is used in [[Logistic regression]]

## Considerations

- The step function is not continuous at x = 0, so it can make it challenging to work with in some mathematical contexts
- The step function is non-differentiable at x = 0, which can be a problem in optimization algorithms that rely on derivatives
- In the context of neural networks and Machine learning, the non-differentiability at x = 0, makes this function not suitable for **Gradient-Base Learning** algorithms like **Backpropagation**.
