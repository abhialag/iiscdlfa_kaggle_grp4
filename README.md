# iiscdlfa_kaggle_grp4
IISC DLFA Kaggle competition Sentence Prediction Group 4

Mini Project Notebook: Irrelevant/inappropriate Questions Classification using Deep Neural Networks.
Learning Objectives
At the end of the mini-hackathon, you will be able to :

perform data preprocessing/preprocess the text
represent the text/words using the pretrained word embeddings - Word2Vec/Glove
build the deep neural networks to classify the questions as Irrelevant/inappropriate or not
Dataset
The challenge in this competition is to predict whether a question asked on a well known public forum/platform is irrelevant/inappropriate or not.

A irrelevant/inappropriate question is defined as a question intended to make a statement and not with a purpose of looking for helpful/meaningful answers. The following are some of the characteristics that can signify that a question is irrelevant/inappropriate:

Based on false information, or contains absurd assumptions
Does not have a non-neutral tone
Has an exaggerated tone to underscore a point about a group of people
Is rhetorical and meant to imply a statement about a group of people
Is disparaging or inflammatory against an individual or a group of people
Uses sexual content (such as incest, pedophilia), and not to seek genuine answers
Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
Based on an unrealistic premise about a group of people
Is not grounded in reality
The training dataset includes the questions 1044897 that was asked, and whether it was identified as irrelevant/inappropriate (target = 1) or as relevant/appropriate (target = 0). The test dataset consists of approximately 261000 questions.

The training data might be imbalanced or noisy. They are not guaranteed to be perfect. Please take the necessary actions/steps while building the model.

Description
This dataset has the following information:

qid - unique question identifier
question_text - the text of the question asked in the well known public forum/platform
target - a question labeled "irrelevant/inappropriate" has a value of 1, otherwise 0
Problem Statement
To perform classification of approximately 261000 questions asked on a well known public form using Deep Neural Networks such as RNN/CNN/BERT/LSTM as 'irrelevant/inappropriate' questions or 'relevant/appropriate' questions

