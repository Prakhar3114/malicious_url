# Detection_of_Malicious_URL

## Problem Statement

<!-- wp:paragraph -->
<p>In this case study, we address the detection of malicious URLs as a multi-class classification problem. In this case study, we classify the raw URLs into different class types such as benign or safe URL, phishing URL, malware URL, or defacement URL. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>As we know machine learning algorithms only support numeric inputs so we will create lexical numeric features from input URLs. So the input to machine learning algorithms will be the numeric lexical features rather than actual raw URLs. If you don't know about lexical features you can refer to <a href="https://stackoverflow.com/questions/33282094/differences-between-lexical-features-and-orthographic-features-in-nlp" target="_blank" aria-label="undefined (opens in a new tab)" rel="noreferrer noopener nofollow">this </a>discussion about a lexical feature in StackOverflow.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>So, in this case study, we will be using three well-known boosting machine learning classifiers namely <strong>XGBoost</strong>, <strong>Light GBM</strong>, <strong>Gradient Boosting Machines</strong>. </p>
<!-- /wp:paragraph -->

## About Data

For training and testing machine learning algorithms, we have used a huge dataset of 651,191 URLs, out of which 428103 benign or safe URLs, 96457 defacement URLs, 94111 phishing URLs, and 32520 malware URLs. 

Dataset is available at kaggle https://www.kaggle.com/sid321axn/malicious

