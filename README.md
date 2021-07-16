# Introduction

The [World Well-Being Project](http://wwbp.org/) is an inter-disciplinary effort among computer scientists, psychologists, and statisticians. Based out of the University of Pennsylvania’s Positive Psychology Center and Stony Brook University’s Human Language Analysis Lab, the WWBP develops scientific and programmatic methods for measuring physical and psychological health using social media data.

We were inspired by the great work that the WWBP does in the health outcomes space. For example, the researchers at the WWBP has successfully demonstrated that machine learning models trained on twitter data are able to predict [heart disease mortality rates](https://cardio.jmir.org/2021/1/e24473) and [excessive alcohol use.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0194290)

Following in that theme, we were interested to investigate if there is a correlation between twitter data and COVID case rates. In the end, we did find a strong correlation between TFIDF scores for twitter ngrams + COVID case rates, as well as sentiment scores and COVID case rates.

# Instructions

The Twitter Terms of Service prevent us from providing the full tweet json objects publicly. To run this notebook, you need that data. Please contact us if you wish to discuss using our data. 

The easiest way to use this code is to run the notebook in Google Collab and upload the data from this repository to your Google Drive account. The notebook will then walk through the process step-by-step.
