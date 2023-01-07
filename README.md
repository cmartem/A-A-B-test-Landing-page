# A/A/B-test Landing page
 task: evaluate impact of new features on website
 
Problem
We have an upload from the analytics system with events on the site. We need to evaluate whether the difference in conversion is likely to be significant after the implementation of improvements on the site. We have a dataset assembled from two control and one test group. We need to make sure that the data was split correctly and evaluate the benefit of the design improvements tested on Group B. We do not know the type of improvements.

Multiple test:

 1. verification of the adequacy of a1 and a2. ideally, there should not be a statistically significant difference, otherwise we have a problem, something went wrong during the entire experiment, which means we need to redo it.
“The main goal of the A/A test is to show whether the results of the experiment can be trusted, which will be run under the same conditions, but with different page variations. If during the A / A test it was not possible to identify the winner, you can run an A / B test. Otherwise, you will have to check the service settings and the homogeneity of the sample. Thus, the A/A test provides benchmark data to test the accuracy of the A/B test.” Source

 Z-scores and standard deviation.
Standard deviation is a reflection of the degree of variability in a given dataset. The square root of the variance. That is, it is like a measure of measurement. We do not have "negative meters" or "centimeters". The "size" of the deviation depends on the distribution.

The Z-score reflects the number of standard deviations of a given data point from the mean. That is, it can be negative. Z-value shows in which direction and how much the value deviated. It's like serifs on a ruler that has notches to the left of zero.

 2. ab-test: we check if there is a difference (and in what direction) in the indicators of the group B sales funnel, on which the font update was rolled out.


 Results
1  Data cleaning
There are 244126 records in total. They reflect user actions included in the sales funnel of different devices on the gaming platform. Due to a data collection error, we are losing the portion before August 1, 2019: 15.99%. The study period is until August 7th. Just a week. This is usually not enough to carry out an ab-test, it would already be possible to conclude that the test was not carried out correctly.

Duplicates found in groups: b 165 a2 125 a1 123 The share of duplicates 0.0017 is less than 1%. The decision was made to remove them.

Due to a data collection error, we lose the portion before August 1st: 15.99%

2  Points of growth
Most of the time is lost in the transition from the “Uploaded the main” stage to the “Offer page” stage.

3  A/A-tests
In the compared groups A1 and A2, there are no cases of going beyond the confidence limits.

4  A/B-tests
The introduction of the new font did not result in a statistically significant change in user behavior. You can leave the old font and take on new growth hypotheses.

5  Optional
Additionally, the analysis of the confidence interval for each segment of the samples was carried out.

For the multiple test, the criteria were adjusted: the recommended value of pi-value is 5%.