---
title: "System Properties based Malware Detection using Machine Learning"
authors:
- admin


# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-09-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "An unpublished MSc thesis submitted to the Division of Computing Science and Mathematics,  University of Stirling, United Kingdom, in partial fulfillment for the degree of Master of Science in Financial Technology (FinTech)"
publication_short: "University of Stirling"

abstract: Problem- The Financial Technology (FinTech) sector is one of the most targeted sectors for malicious software (malware) attacks. The COVID-19 pandemic has further exacerbated this issue as the United Nations noted an increase in cybercrime by 600%. Traditional malware detection methods have become obsolete due to the rapid development of polymorphic and metamorphic malware that automatically change its shape and produces several signatures for the same malware. Objectives- Against this background, it was the objective of this research to detect malware based on system properties using machine learning  algorithms namely Extreme Gradient Boosting (XGBoost), Multi-layer Perceptron (MLP), Decision Tree and Logistic Regression, ascertain the best classiffier, tune the model hyperparameters and determine the most important features in detecting malware based on system properties. Methodology- The methodology utilized was a modified version of the CRoss-Industry Standard Process for Data Mining (CRISP-DM). The data used was a real world malware data curated by Microsoft and hosted on Kaggle. The data was summarized, explored and analysed using univariate, bivariate and multivariate analysis. Furthermore, the data was cleaned by removing features that had sufficiently high number of missing values and imbalance class. Missing values below the threshold was replaced and 9 new features were created. 10% of the entire data was randomly selected, encoded using label and frequency encoding and modelled. A train test split of 70:30 was used alongside Gridsearch with 5-fold cross validation to search for the optimal hyperparameters. Achievements- The results showed that machine learning algorithms were effective in detecting malware based on system properties. Results after hyperparameter tuning showed that XGBoost performed better based on AUC-ROC value, followed by MLP, decision tree and with logistic regression being the least. In addition, the most improved model after tuning based on AUC-ROC difference was decision tree, next to XGBoost, logistic regression and MLP. Furthermore, the most important feature was “SmartScreen" using gain, “AvProductsInstalled" using over, and “AvSigVersion" using cover.

# Summary. An optional shortened abstract.
summary: machine learning, malware analysis, malware detection, cyber security, FinTech

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**My Thesis**]'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
