# Module 20 Report

## Overview of the Analysis

Lending institutions expect borrowers to honor their commitment to returning assets or repaying loans, as failure to do so poses credit risk and potential financial losses. Various methods are employed by lenders to assess this risk, but this analysis focuses on employing Machine Learning to evaluate a dataset of previous lending transactions from a peer-to-peer lending service provider, with the aim of constructing a model capable of accurately determining borrower creditworthiness. Using the lending company's dataset, a Logistic Regression Model was developed, achieving a notable accuracy score of 95%. However, despite its high accuracy, the model exhibits a lower recall value for non-healthy loans (0.91) compared to healthy ones (0.99), suggesting a bias toward predicting loans as healthy rather than identifying non-healthy ones. This bias can be attributed to the dataset's imbalance, where healthy loans outnumber non-healthy ones significantly. Given its widespread applicability in predicting target variable probabilities in classification tasks, the Logistic Regression Algorithm was deemed the most suitable choice for this machine learning model.

## Results

The Logistic Regression model, trained on the original dataset, successfully predicted healthy loans with 100% accuracy and non-healthy loans with an 85% accuracy rate.

## Summary

In the quest for an effective loan classification model, lending companies aim for accurate identification of healthy and non-healthy loans to mitigate potential financial risks. Misclassifying healthy loans as non-healthy could result in customer loss, while misidentifying non-healthy loans as healthy may lead to substantial fund losses for the lender. Minimizing false positives becomes crucial for the lending company, as mislabeling non-healthy loans as healthy poses a significant risk of losing provided funds. The confusion matrices highlight this concern, with 56 instances of false positives, where actual healthy loans were incorrectly classified as non-healthy, and 102 instances of false negatives, where actual non-healthy loans were misclassified as healthy.
