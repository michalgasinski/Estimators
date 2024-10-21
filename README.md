# Exponential Distribution and Estimator Convergence Analysis

This project investigates the behavior of various statistical estimators (mean, median, standard deviation) as sample size increases for an Exponential Distribution. The project demonstrates the law of large numbers in action, showing how the estimators converge to the true population values as the sample size grows.
# Estimators
Sample Mean: An unbiased estimator of the true mean.
Sample Median: Asymptotically unbiased as the sample size grows.
Standard Deviation: An estimator of the dispersion of data points around the mean.

# Project Overview
Convergence of Estimators: The script generates samples of increasing sizes (from 30 to 10,000) and computes the mean, median, and standard deviation for each sample. The results are then smoothed using a rolling window to clearly visualize how the estimators converge to the true population values as sample size increases. Plotting: The estimators are plotted against sample size to observe their behavior. The true mean and true standard deviation are plotted as reference lines to show the estimators' accuracy. To highlight the trend in the estimators, a rolling window is applied to the computed values.
# Visualization:
Python's matplotlib is used to visualize the convergence of estimators, providing an intuitive understanding of how sample size impacts estimation accuracy.
# Results:
The plot clearly shows that as the sample size increases, both the mean and standard deviation estimators converge towards their true values. The median, though asymptotically unbiased, converges more slowly than the mean.
# Conclusion:
This project effectively demonstrates the consistency, unbiasedness, and efficiency of estimators using an exponential distribution. It highlights the importance of sample size in statistical analysis and estimator accuracy.
# Future Work:
Extend the analysis to other distributions (e.g., normal, binomial).
