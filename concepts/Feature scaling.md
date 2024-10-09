
## Normalization

is the process of have the data between the range $[0, 1]$. The common practice is apply the next formula $$X' = \frac {X - X_{min}}{X_{max} - X_{min}}$$
	- The result is a value between $(0,1)$
	- Works well when data have normal distribution

## Standardization

Is similar but instance of extract the max an min, we divide by the standard deviation $\sigma$. As result, the range of values are between $[-3,3]$. If we have outliers they are out of this range. The common practice is apply the next formula $$X' = \frac {X - \mu}\sigma$$
	- $\mu$ is the mean of the values
	- $\sigma$ is the standard deviation
	- the result is a value between $(-3, +3)$
	- Works well all the time with all the type of distributions

> [!NOTE] When do it?
> Feature scaling must be done **after** splitting the dataset into the training set and test set in order to avoid leakage information


> [!NOTE] Which one to use
> The recommendations is use **Standardization** most of the time. Normalization just works when the data has a normal distribution.


> [!DANGER] Encoded variables and Feature Scaling 
> We must not apply scaling features for encoded variables or categorical values
