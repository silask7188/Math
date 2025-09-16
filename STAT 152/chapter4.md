# Chapter 4


## Random Variable Tables

### Probability Distribution with Combinations

Example:
Supposed that a box contains $6$ cameras and that $3$ of them are defective. A sample of $2$ cameras is selected at random. Define the random variable $x$ as the number of defective cameras in the sample

$$\frac{C(3,2)*C(3,0)}{C(6,2)}$$



|$x$|$P(x)$|
|-|-|
|$0$|$\dfrac{C(3,0)*C(3,2)}{C(6,2)}$|
|$1$|$\dfrac{C(3,1)*C(3,1)}{C(6,2)}$|
|$2$|$\dfrac{C(3,2)*C(3,0)}{C(6,2)}$|


|$x$|$P(x)$|
|-|-|
|$0$|$.2$|
|$1$|$.6$|
|$2$|$.2$|


Expected Value; $x = 1$ 

### Expected Values

Expected Values of a random variable table are given by the mean!

$$\sum_{i=1}^{n} x_iP(x_i)$$

Dot product also works!
$$x\cdot P(x)$$

### Standard Deviation

$$\sigma^2 = \sum_{i=1}^n (x_i-\mu)^2*P(x_i)$$

Example:

|$x$|$P(x)$|
|-|-|
|$0$|$0.15$|
|$1$|$0.2$|
|$2$|$0.25$|
|$3$|$0.4$|


$$\mu \,= 1.9$$

$$\sigma \,= (0-1.9)^2*.15+(1-1.9)^2*.2+(2-1.9)^2*.25+(3-1.9)^2*.4$$
$$\sigma \,= 1.09$$



## Product Replacement


Step 1: $\text{Expected Cost} = p*C$

Step 2: $\text{EV} = W - \text{Expected Cost}$

Example:
$.4\%$ of products fail, replacement cost of $\$400$. If they offer an extended warranty for $\$34$, what is the companies expected value of each warranty sold?

$$\$34 - (0.004 * \$400) = \$32.40$$



## Binomial Random Variable

Step 1: Identify Parameters
$n = 15$   : Sample Size
$p = .085$ : Probability
$X = ..$   : Affected Size? 

$$X \sim \,\text{Binomial}(n = 16, p = 0.085)$$


Step 2: Stdev formula for a binomial variable
For a binomial random variable:

$$\sigma_X = \sqrt{np(1-p)}$$

Step 3: Plug in

$$\sigma_X = \sqrt{15*.085*(1-.085)}$$
$$\sigma_X = \sqrt{1.1667}$$

## Binomial Distribution

The number of successes in $n$ independent Bernoulli trials has a binomial distribution.

Suppose:
- N independent trials
- Each trial can result in one of two outcomes

$P(\text{success}) = p$, and this is constant from trial to trial
$$P(\text{failure}) = 1 - p$$
$$X = \text{Number of successes in} n \text{trials}$$

Then $X$ has a binomial distribution:

$$P(X=x) = C(n,x)p^x(1-p)^{n-x}$$
for $x = 0,1,2,...,n$

$$\mu \,= E(x) = np$$
$$\sigma^2 = np(1-p)$$

Example:
A die is rolled 3 times.
What is the probability 5 comes up exactly twice?

Success: rolling 5
Failure: rolling !5
X: number of 5s in 3 roles
X has a binomial distribution with $n=3$ and $p=1/6$

$$P(X=2) = C(3,2)(1/6)^2(1-1/6)^{3-2}$$
$$P(X=2) = .0694$$

