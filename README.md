# kaggle_NaturalLanguageProcessingDisasterTweets

https://www.kaggle.com/c/nlp-getting-started/overview



# Overview

## Evaluation

Submissions are evaluated using [F1](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) between the predicted and expected answers.

F1 is calculated as follows:


$$
F_1=2*\frac{precision * recall}{precision + recall}
$$
where:
$$
precision = \frac{TP}{TP+FP}
$$

$$
recall = \frac{TP}{TP+FN}
$$

# Data

### What should I expect the data format to do?

Each sample in the train and test set has the following information:

- The `text` of a tweet
- A `keyword` from that tweet (although this may be blank!)
- The `location` the tweet was sent from (may also be blank)



### Files

- train.csv - the training set
- test.csv - the test set
- sample_submission.csv - a sample submission file in the correct format

### Columns

- `id` - a unique identifier for each tweet
- `text` - the text of the tweet
- `location` - the location the tweet was sent from (may be blank)
- `keyword` - a particular keyword from the tweet (may be blank)
- `target` - in train.csv only, this denotes whether a tweet is about a real disaster (`1`) or not (`0`)

