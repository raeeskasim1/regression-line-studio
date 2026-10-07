# Regression Line Studio

Place points, fit a line, and see how one outlier can tug an entire model.

## Run

Open `index.html` in a modern browser. HTML, CSS, and JavaScript are all in that file. No server, packages, internet connection, API key, build step, or downloaded model is required.

## Try it

Add a point far from the sample trend and inspect the changed line. Clear the board and create an exactly linear dataset.

## How it works

Ordinary least squares fits slope using covariance divided by x variance, then calculates the intercept and mean squared residual. Fitting is unavailable for fewer than two points or zero x variance. Vertical residuals are drawn as fine lines. The synthetic data is generated locally.

