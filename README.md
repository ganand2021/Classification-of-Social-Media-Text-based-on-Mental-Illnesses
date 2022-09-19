
# Classification of Social Media Text based on Mental Illnesses

CIS 519 - Final Project

## Description

Mental Health problems are a significant public health concern. Automated text analysis of mental-health content aims to enhance medical decision-making, public health policy, and health care delivery. We built a dataset curated by scraping text data from various mental-health subreddits. The augmented dataset contains roughly 23.5k samples, and we modelled it on different model architectures, including Transformer models, LSTMs, SVMs etc., for multi-label classification. From our observation, we noticed that DeBERTa produced the best set of performance metrics and gave us an F1 Score of 0.902. Our primary contribution to this idea lies in augmenting the initial dataset to include more potential categories and a thorough comparative analysis of different models to identify the best among them for this task.
## Team Members

* [Gopik Anand](https://github.com/ganand2021) 
* [Arvind Balaji Narayan](https://github.com/narvind24/)
* [Sumiran Bhasin](https://github.com/sumiranb).
## Repo Content Explanation

The **Dataset** folder consists of the text content that is used to train the models. They should be in the working directory of the Jupyter Notebooks for the code to execute as expected.

The **Models** folder consists of the independent jupyter notebooks for each model we trained for this project which can be executed as a whole as long as the data exists in the working directory.
## Results

| *Model Name*     | *Validation Accuracy* | *F1 Score*     |
| :---            |    :----:           |          ---:|
| Naive Bayes            |    72.02           |          0.735|
| Electra            |    77.00           |          0.77|
| SVM            |    78.05           |          0.782|
| TextCNN            |    79.65           |          0.803|
| DistillBERT            |    81.19           |          0.812|
| BiLSTM            |    81.79           |          0.817|
| Canine            |    84.52           |          0.845|
| ALBERT            |    84.49           |          0.845|
| XLM-RoBERTa            |    84.69           |          0.846|
| BERT            |    86.62           |          0.866|
| XLNet            |    86.74           |          0.867
| RoBERTa            |    87.4           |          0.874
| GPT-2            |    88.12           |          0.881|
| **DeBERTa**            |    **90.33**           |          **0.902**|