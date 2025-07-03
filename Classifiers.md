2025-06-0700:10
Tags:-[[ML]] 
Status:-

### Bayes Classifier
$$
Pr(Y = 1|X = x_{0})
$$

for binary classification
if the equation is greater than 0.5 it belongs to Class 1, or class 2 otherwise
The Bayes classifier produces the lowest possible test error rate, called the Bayes error rate(0.1304)

I n theory we would always like t o predict qualitative responses using the Bayes classifier. But for real data, we do not know the conditional distribution of Y given X, and so computing the Bayes classifier is impossible
### K-Nearest Neighbours

this also uses bayes classifier to an extent 
$$
	P r (Y = j|X = x_{o}) = \frac{1}{K} \Upsigma_{i\epsilon N}
I(y_{i} =j).
$$
where K is number of Neighbours
## References
