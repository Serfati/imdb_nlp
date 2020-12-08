<img src="https://in.bgu.ac.il/marketing/graphics/BGU.sig3-he-en-white.png" height="48px" align="right" /> 
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/IMDB_Logo_2016.svg/575px-IMDB_Logo_2016.svg.png" height="70px"/> 

  
  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Serfati/imdb_sentiment_analysis/blob/master/IMDB.ipynb) ![](https://img.shields.io/apm/l/atomic-design-ui.svg?)
# Description  

This repository contains simple yet efficient solution for sentiment polarity analysis of IMDB dataset with TfIdfVectorizer and Many ML models such as SVM, NB and Kmeans.

Sentiment analysis is a challenging subject in machine learning. People express their emotions in language that is often obscured by sarcasm, ambiguity, and plays on words, all of which could be very misleading for both humans and computers

## Dataset 
The labeled data set consists of 50,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of 0, and rating >=7 have a sentiment score of 1. No individual movie has more than 30 reviews. The 25,000 review labeled training set does not include any of the same movies as the 25,000 review test set. In addition, there are another 50,000 IMDB reviews provided without any rating labels.

### Data fields
- review - Text of the review
- sentiment - Sentiment of the review; 1 for positive  and 0 for negative reviews



## ⚠️ Prerequisites  
  
- [Python 3.6](https://www.python.org/download/releases/3.6/)  
- [Git 2.26](https://git-scm.com/downloads/)  
- [PyCharm IDEA](https://www.jetbrains.com/pycharm/) (recommend)  

## 📦 How To Install  
  
You can modify or contribute to this project by following the steps below:  
  
**1. Clone the repository**  
  
- Open terminal ( <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd> )  
  
- [Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) to a location on your machine.  
 ```bash  
 # Clone the repository 
 $> git clone https://github.com/serfati/imdb_sentiment_Analysis.git  

 # Navigate to the directory 
 $> cd imdb_sentiment_Analysis
  ``` 

**2. Install Dependencies**  
  
 ```bash  
 # install with pip/conda 
 $> pip install -r requirments.txt
 ```  

**3. launch of the project**  
  
 ```bash  
 # run 
 $> jupyter notebook IMDB.ipynb
 ```  

---  

> author Serfati
  
## ⚖️ License  
  
This program is free software: you can redistribute it and/or modify it under the terms of the **MIT LICENSE** as published by the Free Software Foundation.  
  
**[⬆ back to top](#description)**
