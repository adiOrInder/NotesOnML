2025-06-1023:17
Tags:-[[ML]]
Status:-

it is the most basic form of estimating quantitatively using linear equation by plotting it through dataset as it is highly biased and has very low Variance 

$$
y = B_{o}+B_{1}x \dots\dots eq.1
$$
as you have many (x,y) using them to estimate the beta of the functions is easy 
RSS is Residual Sum of Squares 
$$
RSS = e_{0}^2 + e_{1}^2 + \dots. + e_{n}^2
$$
where e is difference between the actual y_i and the estimated y_i
these can be used to estinate the values
$$
\hat{\beta}_1 = 

\frac
{\sum_{i=1}^n(x_i - \bar{x})(y_i - \bar{y})}
{\sum_{i=1}^{n}(x_i - \bar{x})^2}
$$
$$
\hat{\beta}_0 = \bar{y} - \hat{\beta}_1 \bar{x}
$$
### Simple Linear Regression
we linearize any component by
$$
y = B_{o}+B_{1}x 
$$
here we assume y as sample population and x as some factor
taking mu as the population mean 
$$
\hat{y}=\hat{\mu}
$$
of one particular set of observations y1,..., yn, $\hat{\mu}$ might
overestimate $\mu$ , and on the basis of another set of observations $\hat{\mu}$, i might underestimate $\mu$ . As this is very biased no so good for estimation

so we estimate $\hat{\beta}_1$ and $\hat{\beta}_0$ which will be more accurate  

$$
SE(\hat{\beta}_0)^2 = \sigma^2 \left[ \frac{1}{n} + \frac{\bar{x}^2}{\sum_{i=1}^{n} (x_i - \bar{x})^2} \right], 
$$
$$
{SE}(\hat{\beta}_1)^2 = \frac{\sigma^2}{\sum_{i=1}^{n} (x_i - \bar{x})^2}
$$

## References
Page 84 on Introduction to Statistical Learni