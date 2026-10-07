# Regression Line Studio

Place points, fit a line, and see how one outlier can tug an entire model.

https://raeeskasim1.github.io/regression-line-studio/

## Try it

Add a point far from the sample trend and inspect the changed line. Clear the board and create an exactly linear dataset.

## How it works

Ordinary least squares fits slope using covariance divided by x variance, then calculates the intercept and mean squared residual. Fitting is unavailable for fewer than two points or zero x variance. Vertical residuals are drawn as fine lines. The synthetic data is generated locally.

