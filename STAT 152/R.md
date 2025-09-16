```r
# Comb                    
choose(n, r)

# Generation combinations
combinations(n = n, r = 2, repeats.allowed = TRUE)

# Binomial Distribution
choose(n,k) * p**k * (1-p)**(n-k)$
dbinom(successes, size, prob)

# stdev given x Px
mu <- x*Px
std <- sqrt(sum((x-mu)**2 * p))

# mean given x Px
mu <- x %*% Px

# hypogeometric
dhyper(x,m,n,k)
x: successes
m=items in pop with favorable
n=items in pop without
k=sample size

```


