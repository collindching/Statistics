# Covariance and Correlation

Firstly,

- The absence of a relationship between two random variables is called independence and
- The presence of a relationship between two random variables is called nonindependence

In the presence of a relationship, we're naturally, interested in measuring the direction and magnitude of that relationship. Two measures are covariance and correlation.

Covariance of random variables X and Y is defined by 

$$Cov(X, Y) = E((X-\mu_x)(Y-\mu_y))$$

Correlation of random variables X and Y is defined by 

$$\rho_{XY} = \frac{Cov(X,Y)}{\sigma_X \sigma_Y}$$

$\rho_{XY}$ is called the correlation coefficient, and it is a restriction of covariance between [-1, 1].

### Quick interpretation

One simple way to think of covariance is that when the absolute value of $X$ and $Y$ are large, the magnitude of covariance is large. 

But if $X$ and $Y$ tend to have high magniudes in opposite directions, the covariance is negative. 

Keep in mind, covariance is based on deviations from the mean of each random variable.

### Thinking through sign of $Cov(X,Y)$ 

When $X > \mu_x$ and $Y > \mu_y$ are likely to be true together, then $Cov(X, Y)>0$. This is because $(X-\mu_x)(Y-\mu_y)$ will be positive.

Conversely, when $X > \mu_x$ and $Y < \mu_y$ is more likely, then $Cov(X, Y)<0$, because $(X-\mu_x)(Y-\mu_y)$ will be negative.