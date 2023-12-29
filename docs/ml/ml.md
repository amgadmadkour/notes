# Machine Learning

## What is Machine Learning?

> Machine Learning is the field of study that gives computers the ability to learn without being explicitly programmed. - Arthur Samuel, 1959

From an engineering perspective, machine learning can be defined as:

* **P**: Performance
* **T**: Task
* **E**: Experience

For example, a **spam filter** is a *task*, and the *performance* is the **accuracy** of the filter. The *experience* is the **training data** that the filter is trained on. The goal of machine learning is to improve the performance of a task by learning from experience. In the case of the spam filter, the goal is to improve the accuracy of the filter by learning from training data.

Machine learning is suitable for the following problems

* Require a lot of hand-tuning or long lists of rules.
* Complex where traditional methods do not work well.
* Fluctuating over time where the data changes frequently.
  
The alternative to machine learning is **hand-crafted rules**. For example, a spam filter could be built by hand-crafting rules such as:

* If the email contains the word "coupon", then it is spam.
* If the email is from a known spammer, then it is spam.
* If the email is from a friend, then it is not spam.
  
The problem with hand-crafted rules is that they are **brittle**. For example, if the word "coupon" is replaced with "koupon", then the rule will not work. Machine learning is more robust because it learns which words are associated with spam from the data.

## Tasks

Some of the common tasks include:

* [Classification](task/classification.md): The system classifies instances into classes.
* [Regression](task/regression.md): The system predicts a value given a set of features.
* [Clustering](task/clustering.md): The system groups similar instances into clusters.
