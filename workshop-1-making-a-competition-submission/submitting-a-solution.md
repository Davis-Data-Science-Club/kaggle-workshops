# Submitting Your Solution

<!-- JS to display latex equations within document -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS_CHTML"></script>

## Score Evaluation

We can see how our score will be evaluated [here](https://www.kaggle.com/c/restaurant-revenue-prediction/overview/evaluation).

\\[\text{RMSE} = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2} \\]

The square will punish large errors compared to Mean Absolute Error.

## Submission File

Output CSV should have two columns, `ID` and `Prediciton` for each restaurant in
the dataset. Our output should have 100,000 rows [0, 99,999].

```
Id, Prediction
0, 1.0
1, 1.0
2, 1.0
...
```

## Submission Score

You will automatically end up with two scores, a 'public' and 'private' score.

The 'public' score is compared against 1% of the test data, this is not the score
for the official leaderboard.

The 'private' score is compared against 99% of the test data, this will be the
official leaderboard score.

The sampleSubmission.csv will result in a score of:

| Private | Public |
|-|-|
| 1883099.54122 | 1929245.11373 |
|-|-|
