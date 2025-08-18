# Fair AI: Estimation of Biasness in AI Models

This project explores fairness and bias in AI models through systematic evaluation and empirical experimentation. Using neural network architectures like **LeNet-5**, **ResNet-18**, and **DeepFace**, the study aims to quantify and mitigate demographic disparities in model predictions across datasets such as MNIST, CIFAR-10, and facial recognition benchmarks.

## Objective

To develop a structured framework for:

* Measuring AI bias
* Understanding its causes
* Evaluating it using fairness metrics
* Proposing improvements for equitable AI

## Key Fairness Metrics

* **Demographic Parity**
* **Equality of Opportunity**
* **Equalized Odds**
* **Predictive Parity**
* **Treatment Equality**
* **Wasserstein Distance**

## Experiments

* **LeNet-5** on MNIST Digits & Fashion
* **ResNet-18** on CIFAR-10
* **DeepFace** for Gender & Ethnicity classification
* **Vision Transformer (ViT)** for Facial Expression classification

## Findings

* All models showed varying degrees of bias.
* Simpler models (e.g., LeNet-5) struggled more with subtle feature variations.
* Bias was observed across both overrepresented and underrepresented classes.
* Fairness trade-offs exist between precision, recall, and group fairness metrics.
* Any one metric is not sufficient to measure biasness across various aspects, so a framework of all combined will work well. 

## Team

* Keshav Lohani, Goransh Barde, Darshan Vanjara, Trilok Meena, Aman Raj
  Supervised by [**Dr. K.P. Singh**](https://profile.iiita.ac.in/kpsingh/), IIIT Allahabad.


