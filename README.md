# Spam-Detection-using-Naive-Bayes


Naive Bayes classifiers are widely used in email filtering to distinguish spam emails. They typically employ a method called "bag of words" which is common in text classification. These classifiers operate by associating specific tokens (usually words) with either spam or non-spam emails. They then apply Bayes' theorem to estimate the likelihood of an email being spam.

This approach to spam filtering is fundamental and can be customized to suit the email preferences of individual users. It is known for its low rate of falsely identifying legitimate emails as spam, which is generally acceptable to users. Each word has a certain likelihood of appearing in either spam or legitimate emails. Initially, the filter doesn't know these probabilities and needs to be trained. During training, a user must manually categorize new emails as spam or not. The filter then adjusts its database, changing the probabilities for each word's occurrence in spam or non-spam emails.

After training, these word probabilities, or likelihood functions, help determine whether an email falls into one category or the other. The impact of each word on the email's classification as spam is termed its "posterior probability", calculated using Bayes' theorem. The filter then assesses the spam likelihood for each word in the email. If the combined probability of all words surpasses a certain level, the email is labeled as spam.
