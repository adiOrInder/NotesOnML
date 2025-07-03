2025-06-2123:48
Tags:-[[Stats]][[ML]]
Status:-

Entropy quantization of likelihood of an expected value

n-> no of possibility
$$
E(likelihood) = \Upsigma P(x)\log_{n}(\frac{1}{P(x)})
$$



### cross entropy loss function
for finding a gradient descent (minimize)function opposite of likelihood
we find it's mean and multiplying it by -ve
$$
L = - \frac{\left[ y \log(\hat{y}) + (1 - y) \log(1 - \hat{y}) \right]}{m}

$$
y = actual label (0 or 1)
 y^​ = predicted probability that the label is 1
 m is no of data
## References
