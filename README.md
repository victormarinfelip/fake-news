# Fake news detection: An exploration the AI version of an *ad-hominem* fallacy.

Besides going to the lengths of actually verifying the information present in an
article, telling if an article contains fake news or not can be deceptively easy.
In this notebook I show how the presence of certain names (say Donald Trump) or
sources (say Reuters) heavily influence the classiffication of news articles.

This is an obvious *ad-hominem* fallacy (if Reuters says it then it must be true),
and a better method must be designed to make classiffication inmune to the presence
of these *keywords*. After applying the ideas found in [this research paper](https://onlinelibrary.wiley.com/doi/10.1002/spy2.9)
I find a better solution to the problem finding out that the use of more emotional words correlate
with a news article containing false information, which makes way more sense than 
just using the presence of certain keyword like 'Reuters' to tell if the information
is true or not.
