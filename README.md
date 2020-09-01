# TwitterProject - Machine Learning & Analysis for Twitter Bot Detection

## Final Project for Class Foundations of Data Science - FGV

## Team
- Matheus Paes
- Matheus Popst
- Vitória Guardieiro

## Overview and Motivation

Twitter is a massive platform, capable of reaching and influencing millions of people. Agents take advantage of this and operate bots that post on the platform, with intentions that vary from spamming to influencing masses. This work proposes to classify Twitter users as human operated or bot operated, utilizing a range of features obtained from the users’ profiles and the tweets they post.

## Data

We're using the Tweet Bot data collected by My Information Bubble (http://mib.projects.iit.cnr.it/dataset.html). Their terms of use don't allow us to distribute the data.

We only used two of the datasets, due to the variety of types of bots. As we were interested it the challenge to identity the differences between Genuine Accounts and Fake Accounts who were trying to be identified as genuine, we decided that the traditional spambot #1 was the closest to it. The other ones didn't presented great challenges: they were retweeters, spammers of Amazon products, spammers of URLs, etc.

The data we used consisted of .CSVs with data about the users and about tweets made by those users.

## Repository

1) Classification_no_NLP

Uses user data to classify whether a user is a bot or not.

2) NLP_Preprocessing

Preprocesses tweets data and extracts NLP features from them.

3) Classification_with_NLP

Uses tweets data, with the features extracted from NLP_Preprocessing, to classify whether a user is a bot or not.


## Running the code

You first nedd to run NLP_Preprocessing.ipynb to be able to run Classification_with_NLP.ipynb.

You can run Classification_no_NLP.ipynb without running NLP_Preprocessing.ipynb first.

