# Data Science and Public Policy

*******************************************************

### Detecting Fake News

[<img src="https://cdn.factcheck.org/UploadedFiles/fakenews.jpg" width="200">](https://www.factcheck.org/2016/11/how-to-spot-fake-news/)

<br>

##### Comparative textual analysis of fake and real news.


Data comes from [FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet/tree/old-version) and was collected by the fact-checker Politifact.

Project files:

- classifier-politifact.ipynb
  - Models predicting whether in article is fake or real news. Best models achieve 90% accuracy and f1-score.
  
  
- project1.Rmd
  - unigram/bigram analysis of fake and real news articles, correlation analyses, sentiment analysis


- project1.html
  - knitted output file from project1.Rmd 
  
  
- politifact.ipynb
  - script that provides summary statistics on real and fake news
  - i.e average article length, average number of sentences, unique words, etc.
  
  
  
  
*******************************************************


### Analyzing Chicago Crime and 311 Lights Out Data, 2018

[<img src="https://311.chicago.gov/resource/1579238270000/communityLogo" width="200">](https://311.chicago.gov/s/?language=en_US)

<br>

Data comes from [Chicago Data Portal](https://data.cityofchicago.org/):
  - [Crimes - 2001 to Present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/data)
  - [311 Street Lights Out Complaints 2018](https://data.cityofchicago.org/Service-Requests/311-Service-Requests-Street-Lights-All-Out-Histori/zuxi-7xem)


Project files:

- project2.Rmd
  - descriptive crime reported statistics from 2018, spatial analysis of reported crime / arrests and demographics, 311 lights out analysis and its relationship with reported crime rates


- project2.html
  - knitted output file from project2.Rmd 
