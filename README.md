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
[<img src="https://ago-item-storage.s3.us-east-1.amazonaws.com/eab8db8edf284213a957e32358a45fab/2.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLWVhc3QtMSJGMEQCIE%2FTfwloFy23HgEmeSKZWlcqICUsx4Vyc0D82ikZZuIuAiB3Aa60VzJIHuS3jp0LuTti9cphgCkaVaL7whKqQvq04yq0AwhhEAAaDDYwNDc1ODEwMjY2NSIM1NfxKdZwmgdd77Y1KpEDyUDkoRuNeq174293h%2ByZ7ka16rDO8689DW9yyxuWAiVf2xpomvFOWMOPTney%2B4rTbiaiMA7WVXegQqBSCPSMv%2FKQk%2BwS6KjuuczevfYtuV4fFrZYreCh0elS3kmF4N7pajEskD20d0oe9mZWxzaI9vnQkCOfv%2BgfDW7%2F1hr70jeL9uXUkWSeJwzVaSZjJHDGEp6Yc9Fm7C5envHgaSsXsYBhwZHQVMKhUKhq2Uabe3g%2Ffr2nQFv6qelUiSU87NsOSz6HkzI1jFjCk%2FBoIWUPo9wqdZ4pJauMH2Uts6IdPW44nviA%2FQyvx8TogYqpjZnD6%2F7TQHwTzGJa3CWuuKbWsdQqXUuey7e5F0Jm3zU8A%2Bt3o%2BydoNlmED5oE%2B65dKqSe0Blt8OXMisUVihsP%2BpuUklHgRfbu9SySJz1MzXxESLZNSN456zvIqiYKPk9vqhuwn9Z%2FlIxvK71AvhPSetYk8kVo7WZiZxT4nlf3IK4Xk6SaO5SIhIrVnjoaUDcuTEPvaJ%2FDWCWYfvlQDNio57bQMYwwt7pgQY67AEYFO%2FiQtdNZo72O5glyay8fQSKpbSI0Naq1XpiKx%2FaBVA8B7bzCisr%2BVSZ8VebGgcEmZJ8i4G%2BC3I6PcTUafCuGODlwPXPnXh06Jc7VwHqBJaNO669E1o9ZkTxPFMj%2Fa47QY1ch4bl5XEU7gOV72NWOUELu5n4IfdYvYUBcDsfX%2BiVb6cd%2BumO%2FQTctTgZ3vqO37w%2FL55%2F3IQ6%2BINJSVnJ2Lg97%2FIr7Li4NE%2BrHEvQIj9Li72Xk6Mw98zS65gTjuvVQDAjH7HDvUeqkNIvyqE7nzj5GV9KXP22imdARwLMcJDnSQxmfzzIcCK4mg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210227T162930Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAYZTTEKKE7COYH7TP%2F20210227%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e4d227ad6dd732bf6edd9b4d040e7d0f535558fb1aa58ebf3ad3c2ae92bf7532" width="200">](https://chicago.curbed.com/2019/3/8/18254833/chicago-street-lighting-orange-glow)
<br>

Data comes from [Chicago Data Portal](https://data.cityofchicago.org/):
  - [Crimes - 2001 to Present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/data)
  - [311 Street Lights Out Complaints 2018](https://data.cityofchicago.org/Service-Requests/311-Service-Requests-Street-Lights-All-Out-Histori/zuxi-7xem)


Project files:

- project2.Rmd
  - descriptive crime reported statistics from 2018, spatial analysis of reported crime / arrests and demographics, 311 lights out analysis and its relationship with reported crime rates


- project2.html
  - knitted output file from project2.Rmd 