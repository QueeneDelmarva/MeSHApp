# Data Mining Project 2022: MeSH on Demand Application 

## Features to be Implemented 
1. MeSH Recommendation using Logistic Regression and LSTM [~]  -- 20/04/2022
2. Article Ranking using Cosine Similarity [√] -- 30/02/2022
3. Visualization of Terms from PubMed Articles with Scripting [~] -- 20/04/2022

## Progress Development 
### Wednesday, 30 March, 2022 
I've sucessfully developed the second feature of the application by using the TFIDF model. Following a reference found in Kaggle, I was able to get the top 5 articles similar to the requested article based on user input (abstract). 

I have yet to implement the other features as we are still figuring out how. But we do plan to use either the Logistic Regression or LSTM, as well as using the VOSviewer software to visualize the terms in PubMed articles. 

### Wednesday, 20 March, 2022
I was able to do the other two features, although it doesn't meet up with some the the task requirements. 

Instead of using the machine learning models for the MeSH Recommendation, I used a python library called YAKE!. I compared my application with MeSH-on-Demand's official application, and the results were close. Although my application displayed the MeSH terms like in the offical application, it also showed non-MeSH terms. 

For the visualization of terms, I did a simple word cloud data visualization based on the MH coloumn in the csv file. 

There are still improvements to be made, such as: 
1. Feature 2: Change index into PMID
2. Feature 1: Use LR and LSTM
3. Feature 3: Script VOSViewer


#### References Used 
1. Yann Claudel (2020) Find Similar Articles with tf-idf (Version 1 of 1) [Source code]. https://www.kaggle.com/code/yclaudel/find-similar-articles-with-tf-idf/notebook
2. Campos, R., Mangaravite, V., Pasquali, A., Jatowt, A., Jorge, A., Nunes, C. and Jatowt, A. (2020). YAKE! Keyword Extraction from Single Documents using Multiple Local Features. In Information Sciences Journal. Elsevier, Vol 509, pp 257-289
3. Aman Kharwal (2021) Word Cloud from a Pandas DataFrame in Python [Source code]. https://thecleverprogrammer.com/2021/11/11/word-cloud-from-a-pandas-dataframe-in-python/
