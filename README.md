# NLP-Driven Email/SMS Spam Filtering Capstone Project

## Team Members
- Mr. Anubhav Kumar Tiwary (Roll No. = PGD22DS65)
- Mr. Shubham Varudkar (Roll No. = PGD22DS44)

## Project Guide
- Mrs. Poonam Bawake

## Introduction

In a world where digital communication has become indispensable, emails and SMS messages have revolutionized our daily lives. However, they have also given rise to an annoying problem - spam. Spam emails and text messages clutter our inboxes and phones, posing security threats. This project, "NLP-Driven Email/SMS Spam Filtering," addresses this issue by utilizing Natural Language Processing (NLP) and machine learning algorithms to create a robust spam filtering system.

Our goal is to develop an advanced spam detection system that doesn't rely on simple rules or static keywords. Instead, it leverages the complexity of human language, including semantic and syntactic analysis, to make nuanced decisions. This approach adapts to evolving spam tactics, reducing false positives and ensuring important messages aren't mistakenly marked as spam.

Key components include data collection, preprocessing, feature engineering, model selection and training, and integration into email and SMS platforms. The system not only protects users from spam but also from security threats.

This project contributes to NLP-driven spam filtering by exploring innovative techniques and practical applications in cybersecurity and electronic communication management.

## Problem Statement

Our project aims to develop an intelligent spam filtering system for emails and SMS messages using Natural Language Processing (NLP) techniques and machine learning algorithms. The goal is to identify and filter out spam messages effectively, enhancing communication security and reducing unwanted messages.

## Dataset Information

**Overview:** This dataset combines two distinct datasets: the "SMS Spam Collection Dataset" and the "Ling-Spam Dataset" to create a comprehensive dataset for developing a spam filtering system.

**1.) [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset):**
- Source: 5,574 SMS messages collected for SMS spam research.
- Content: Contains labels (ham or spam) and raw text messages.
- Origin: Messages from various sources, including Grumbletext website, NUS SMS Corpus, Caroline Tag's PhD Thesis, and SMS Spam Corpus v.0.1 Big.
- Purpose: Enables the development of SMS spam filtering models.

**2.) [Ling-Spam Dataset](https://www.kaggle.com/datasets/mandygu/lingspam-dataset):**
- Source: Curated from the Linguist List, comprising 2,893 spam and non-spam emails.
- Content: Header information removed, leaving core email text.
- Composition: 2,412 legitimate (ham) emails and 481 spam emails.
- Purpose: This dataset enriches our combined dataset with diverse email and SMS spam and legitimate communications.

Our project uses NLP and machine learning to train a predictive model for classifying incoming texts and emails as spam or legitimate messages, improving communication security and reducing unwanted messages.

## Conclusions and Future Work

**Classifier Performance:**
- The Voting Classifier achieved mean training and testing accuracy of approximately 99.41%, excelling in accurately identifying spam emails.
- The Stacking Classifier exhibited high mean training accuracy (approximately 99.89%) and good testing accuracy (approximately 98.27%), balancing precision and recall.

**Ensemble Learning Effectiveness:**
- Voting and Stacking Classifiers demonstrated the effectiveness of ensemble learning in spam email classification.

**Future Directions:**
- Explore deep learning (CNNs or RNNs) for enhanced spam detection accuracy.
- Investigate unsupervised learning for feature extraction and subtle pattern recognition in spam emails.
- Incorporate NLP techniques to analyze email content, including context and semantics.
- Optimize hyperparameters and thresholds for email notifications to enhance scalability.
- Continuously update the spam detection system to adapt to evolving spamming techniques.

**Robustness and Adaptability:**
- Ensure long-term system effectiveness through regular updates and enhancements.
- Consider additional security measures like data encryption and steganography for user data protection.

**Hybrid Approaches:**
- Explore hybrid machine learning and NLP techniques for more robust spam filters.

**Real-Time Implementation:**
- Investigate implementing the spam classification model in email clients for real-time spam protection.

**Dataset Expansion:**
- Collect diverse samples of spam and non-spam emails to improve model generalization and robustness.
