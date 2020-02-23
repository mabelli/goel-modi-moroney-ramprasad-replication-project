# Replication of Comparative Studies of Detecting Abusive Language on Twitter
Repository for the project on research paper replication in WI 2020 Data Reproducibility course


### CONTRIBUTORS

1. [Aboli Moroney](https://github.com/abolim "Aboli's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0003-1226-3185" href="https://orcid.org/0000-0003-1226-3185" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

2. [Mayank Goel](https://github.com/mickkygoel "Mayank's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0002-2458-910X" href="https://orcid.org/0000-0002-2458-910X" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

3. [Harini Ram Prasad](https://github.com/hariniramp "Harini's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0001-5419-8030" href="https://orcid.org/0000-0001-5419-8030" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

4. [Samarth Modi](https://github.com/samarthjmodi "Samarth's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0003-0681-231X" href="https://orcid.org/0000-0003-0681-231X" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

### CONTENTS

Lately, there has been a lot of effort and research on identifying content that is abusive or offensive on online and social media. Twitter recently published a relatively large and reliable dataset on ‘Hate and Abusive Speech on Twitter’. As Data Scientists, we understand the need to find the best methods and data for identifying such content and flagging it as inappropriate.
 
In this repository, our aim is to reproduce some of the findings in a research paper that performs a comparative study and provides suggestions for using additional features and data for improving such classification of hate and abusive speech using Twitter data.
Using the data and code provided by the authors, we aim to replicate the efficacy and accuracy of Logistic Regression model presented in this paper. The original paper had a comparative study of 5 different machine learning and deep learning algorithms. However, for our replication purpose we chose Logistic Regression model using word-level features only because the author stated that this model outperformed all the machine learning techniques and had an F1-score which was equivalent to the best CNN model. For our project, we also had limited computational resources due to which execution of other machine learning and deep learning models was out of scope.

Citation: Lee, Y., Yoon, S., & Jung, K. (2018). Comparative studies of detecting abusive language on twitter. arXiv preprint arXiv:1808.10245.

URL: https://arxiv.org/abs/1808.10245

Git Repository: https://github.com/younggns/comparative-abusive-lang/blob/master/README.md

### DATA
 
The link to the exact data used in the research is mentioned in the GitHub page by the authors.
The data itself is hosted in another GitHub repository called hatespeech-twitter managed by ENCASE (The organization for the ENCASE (ENhancing seCurity and privAcy in the Social wEb) Horizon 2020 European Research Programme). Following is the link to the repository hosting the data: https://github.com/ENCASEH2020/hatespeech-twitter

The data is present in the csv format, in the file titled hatespeech_labels.csv.
The file contains Tweet IDs of ~100k tweets used in training and testing the models. These IDs should be sufficient to extract all the data that we need to reproduce the research work.
 
Additionally, the owners of the data are open to sharing the full extracted data file upon request via email. In case we are unable to extract the tweets using the available data file, we will try reaching the data owners at their provided email ID (a.m.founta@gmail.com).

### DEPENDENCIES

OS type and version: 
Windows 10 Pro, Version 1903, OS build 18362.535
System type: 64-bit OS, x64-based processor
R version: >=3.6.2

R packages and versions:

|R Package   	    |     Version            |
|---------------|:-----------------------|
|CARET	       |   6.0-84|
|future	        |  1.16.0|
|tm	            |0.7-7|
|quanteda	            |1.5.2|
|Liblinear	            |2.10-8|
|stringr	            |1.4.0|
|here	            |0.1|
|ggplot2	            |3.2.1|
|wordcloud	            |2.6|
|bookdown	            |0.17|
|dplyr	            |0.8.3|
|knitr	            |1.28|

### CONTRIBUTING

We welcome contributions from everyone. Before you get started, please see our contributor guidelines. Please note that this project is released with a [Contributor Code of Conduct](https://github.com/abolim/Reproducibility-Research-Replication/blob/master/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

