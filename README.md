Detection_of_Malicious_URLs_using_Lexical_features
Problem Statement
In this case study, we address the detection of malicious URLs as a multi-class classification problem. In this case study, we classify the raw URLs into different class types such as benign or safe URL, phishing URL, malware URL, or defacement URL.

As we know machine learning algorithms only support numeric inputs so we will create lexical numeric features from input URLs. So the input to machine learning algorithms will be the numeric lexical features rather than actual raw URLs. If you don't know about lexical features you can refer to this discussion about a lexical feature in StackOverflow.

So, in this case study, we will be using three well-known boosting machine learning classifiers namely XGBoost, Light GBM, Gradient Boosting Machines.

About Data
For training and testing machine learning algorithms, we have used a huge dataset of 651,191 URLs, out of which 428103 benign or safe URLs, 96457 defacement URLs, 94111 phishing URLs, and 32520 malware URLs. Figure 2 depicts their distribution in terms of percentage. As we know one of the most crucial tasks is to curate the dataset for a machine learning project. We have curated this dataset from five different sources.

For collecting benign, phishing, malware and defacement URLs we have used URL dataset (ISCX-URL-2016) For increasing phishing and malware URLs, we have used Malware domain black list dataset. We have increased benign URLs using faizan git repo At last, we have increased more number of phishing URLs using Phishtank dataset and PhishStorm dataset As we have told you that dataset is collected from different sources. So firstly, we have collected the URLs from different sources into separate dataframe and finally merge them to retain only URLs and their class type.

The final pre-processed dataset is available at kaggle https://www.kaggle.com/sid321axn/malicious
