---
title: "Learning to Validate the Predictions of Black Box Machine Learning Models on Unseen Data"
collection: publications
permalink: /publication/2019-07-05-HILDA-Workshop-Paper
excerpt: 'When end users apply a machine learning (ML) model on new unlabeled data, it is difficult for them to decide whether they can trust its predictions. Errors or shifts in the target data can lead to hard-to-detect drops in the predictive quality of the model. We therefore propose an approach to assist non-ML experts working with pretrained ML models. Our approach estimates the change in prediction performance of a model on unseen target data. It does not require explicit distributional assumptions on the dataset shift between the training and target data. Instead, a domain expert can declaratively specify typical cases of dataset shift that she expects
to observe in real-world data. Based on this information, we learn a performance predictor for pretrained black box models, which can be combined with the model, and automatically warns end users in case of unexpected performance drops. We demonstrate the effectiveness of our approach on two models – logistic regression and a neural network, applied to several real-world datasets.'
date: 2019-07-05
venue: 'the 4th Workshop on Human-In-the-Loop Data Analytics (HILDA)'
citation: 'S. Redyuk, S. Schelter, T. Rukat, V. Markl, F. Biessmann (2019) Learning to Validate the Predictions of Black Box Machine Learning Models on Unseen Data. HILDA’19, Amsterdam, Netherlands'
---
Abstract

When end users apply a machine learning (ML) model on new unlabeled data, it is difficult for them to decide whether they can trust its predictions. Errors or shifts in the target data can lead to hard-to-detect drops in the predictive quality of the model. We therefore propose an approach to assist non-ML experts working with pretrained ML models. Our approach estimates the change in prediction performance of a model on unseen target data. It does not require explicit distributional assumptions on the dataset shift between the training and target data. Instead, a domain expert can declaratively specify typical cases of dataset shift that she expects
to observe in real-world data. Based on this information, we learn a performance predictor for pretrained black box models, which can be combined with the model, and automatically warns end users in case of unexpected performance drops. We demonstrate the effectiveness of our approach on two models – logistic regression and a neural network, applied to several real-world datasets.

[Download paper here](http://sergred.github.io/files/hilda.reds.pdf)
