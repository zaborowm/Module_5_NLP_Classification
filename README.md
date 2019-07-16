# Module_5_NLP_Classification
MaryJo Zaborowski &amp; Chris Riggio

## Inspiration
We noticed a pattern in scientific literature.

When biomedical innovation happens, we see an almost-exponential increase in publications, followed by many clinical trial starts.

If we can predict  innovation from publication velocity...
1. Investors can predict stock price increases
2. Wise biomedical companies can gain early-mover advantage
3. Patients can benefit from accelerated innovation 

## This Project
Automate an intelligent way to triage publications into innovation categories

Objective: Develop a classification model through a machine learning approach to automate the categorization of new literature.
Why: PubMed has 29M articles, and updates at 200K articles/month. Need automation for this step.

Target Innovation Topics: Lung Cancer & ALK; Heme Malignancies & CAR-T; Lung Cancer, Melanoma & PDL-1; Psoriasis & Th17 Pathway

## Approach
1. Collect, clean, and aggregate literature abstracts as training and testing data
2. Prepare training corpus (Stop words, Lemmatization, Bigrams and Trigrams)
3. Generate models (LDA unsupervised, Naïve Bayes Classifier)
4. Visualize and assess quality of prediction and Refine models as needed

## Summary
1. Built and evaluated multiple models - unsupervised and supervised.
2. Visualization is key to assessing model performance.
3. The supervised (Naive Bayes) with GridSearch parameter optimization performed best at 95% accuracy. 





