# Data Science and Public Policy

*******************************************************

### Detecting Fake News

[<img src="https://cdn.factcheck.org/UploadedFiles/fakenews.jpg" width="200">](https://www.factcheck.org/2016/11/how-to-spot-fake-news/)

<br>

##### Comparative textual analysis of fake and real news.


Data comes from [FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet/tree/old-version) and was collected by the fact-checker Politifact.

Project files:

* classifier-politifact.ipynb
  Models predicting whether in article is fake or real news. Best models achieve 90% accuracy and f1-score.
  
* project1.Rmd
  unigram/bigram analysis of fake and real news articles, correlation analyses, sentiment analysis

* project1.html
  knitted output file from project1.Rmd 
  
* politifact.ipynb
  script that provides summary statistics on real and fake news
  i.e average article length, average number of sentences, unique words, etc.