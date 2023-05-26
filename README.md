# Central Limit Theorem Simulation

The purpose of this study is demonstrate the Central Limit Theorem by simulating die rolls!

### The Central Limit Theorem

This theorem is an extremely important theorem in Statistics, which establishes that, for random independent samples, the standardized sample mean will be normally distribuited, assuming the sample size is large enough.

In other words, lets assume we have N random samples $X_1, X_2,..., X_N$ drawn from a pupulation with mean $μ$ and variance $\sigma^2$ with $\bar X_N$ being the sample mean of first $N$ samples, then the distribution $Z = \lim_{N\to \infty} (\frac{\bar X_N - μ}{\sigma \bar X})$, with $\sigma \bar X = \frac{\sigma}{\sqrt N}$, is a standard normal distribution.

### Rolling the Dice

To understand how the theorem works, we will be simulating fair die rolls, with equally possible results of $[1,2,3,4,5,6]$. Also, we'll be working with a number of samples = 10.000 and variable samples sizes. For example, if we have a sample of size 1 and number of samples 10.000, that means we are going to produce the average of 1 roll $10.000$ times.

Another example, if we have a sample of size 2 and number of samples 10.000, it means that we are rolling 2 dices for $10.000$ times.

With this, we can simulate the average of N rolls, for 10.000 times, and plot into a histogram to see its distribution.

> Sample size = 1 (Rolling 1 fair dice for $10.000$ times)

![1](https://github.com/francismelojr/Simulacao-Teorema-Central-do-Limite/assets/131476419/c2db72a0-d918-41a1-b6f0-dc2991e50812)

As we can notice, the means are equally distributed.

> Sample size = 2 (Rolling 2 fair dices and taking their average for #10.000$ times)

![2](https://github.com/francismelojr/Simulacao-Teorema-Central-do-Limite/assets/131476419/437e7bda-35b3-4eb6-b949-b7fed8c24013)

As N gets higher, the distribution tends to standard normal distribution. We can observate this by increasing the value of N (taking the average of more dice rolls for $10.000$ times).

> Samples size = 5

![5](https://github.com/francismelojr/Simulacao-Teorema-Central-do-Limite/assets/131476419/f7d530a4-865e-4c46-865b-2ce922ac71d5)

> Sample size = 10

![10](https://github.com/francismelojr/Simulacao-Teorema-Central-do-Limite/assets/131476419/92edd07e-fd59-4f47-9880-7964bed6b888)

> Sample size = 50

![50](https://github.com/francismelojr/Simulacao-Teorema-Central-do-Limite/assets/131476419/01ee56a4-69c0-40b5-9bb1-232bd10ab32e)

> Sample size = 100

![100](https://github.com/francismelojr/Simulacao-Teorema-Central-do-Limite/assets/131476419/790bc46a-f0b8-4438-b4f6-010d75fff59d)
