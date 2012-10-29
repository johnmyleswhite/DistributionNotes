# The Arcsine Distribution

## Introduction

The Arcsine distribution is a distribution over the interval \\([-1, 1]\\). It is an extension of a specific parameterization of the Beta distribution expanded and translated to cover a larger interval. 
Specifically, the Arcsine distribution is a variant on the Beta(1/2, 1/2) distribution. It shares with this distribution two peaks located at the far extremes of its supports: one mode lies at -1 and another at +1.

## Cumulative Distribution Function
$$
\frac{2}{\pi} \sin^{-1}(\sqrt{\frac{x + 1}{2}})
$$

## Probability Density Function
On its support, the PDF of the Arcsine distribution is given by
$$
\frac{1}{\pi \sqrt{1 - x^2}}
$$

## Random Number Generation
As noted in Devroye IX.7, one can generate random samples from the Arcsine distribution by transforming draws from the uniform distribution. Given a draw, \\(u\\), from the uniform distribution, one can generate a draw, \\(a\\), from the Arcsine distribution using the transformation:

$$
a = \sin(2\pi u)
$$

## Quantile Function
On its support, the quantiles of the Arcsine distribution are given by

$$
2 \sin(\frac{\pi}{2}p)^{2} - 1
$$

This is the inverse of the CDF described above.

## Moments and Median
* The mean of the Arcsine distribution is \\(0\\).
* The variance of the Arcsine distribution is \\(\frac{1}{2}\\).
* The skewness of the Arcsine distribution is \\(0\\).
* The kurtosis of the Arcsine distribution
* The median of the Arcsine distribution is \\(0\\).

# Alternatives and Generalizations
One popular form of the Arcsine distribution is over the interval \\([0, 1]\\). In that case, it is identical to the Beta(1/2, 1/2) distribution.

It is possible to add scale and location parameters to the Arcsine distribution to create a Generalized Arcsine distribution.

# References

Devroye, IX.7 Non-Standard Distributions
