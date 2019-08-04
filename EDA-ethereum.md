## Exploratory Data Analysis of the Ethereum value 

This project was originally created in February 2018 and has been updated several times in 2018 and 2019. 

**Project description:** 

The Ethereum is the second most popular cryptocurreny after the Bitcoin. It has gain a lot of attention last year. But while some see it as another potential investment, others predict it to be a more sophisticated version of its predecessor. The reason why leads in the general use of this technolgoies: Bitcoin is used a currency and Ethereum as "a ledger technology that companies are using to build new programs" (source: https://hackernoon.com/the-primary-difference-between-ethereum-and-bitcoin-a-beginners-guide-8a892afb7a4). In addition of feeding the aspirations of a large crowd, Ethereum drew the attention of a group called 'The Enterprise Ethereum Alliance', which is super-group of "Fortune 500 companies that have all agreed to work together to learn and build upon Ethereum’s blockchain technology — otherwise referred to as “smart contract” technology".

This time, we will solely look at Ethereum as a cryptocurrency and its market value. 

Our main assumption is: **The Ethereum value can be predicted with historical values, other cryptocurrencies'indexes or other markets**


**Previous Analysis**

Most of the existing analysis on cryptocurrencies focus on the Bitcoin. 

1. MIT computer Scientists have predicted the fluctuations of the Bitcoin and have bet every two seconds accordindly to the predictions. (http://news.mit.edu/2014/mit-computer-scientists-can-predict-price-bitcoin) “We needed publicly available data, in large quantities and at an extremely fine scale,” says Shah, the Jamieson Career Development Associate Professor of Electrical Engineering and Computer Science. “We were also intrigued by the challenge of predicting a currency that has seen its prices see-saw regularly in the last few years.” They used historical data for it.

2. Predicting the fluctuations with Twitter Sentiment Analysis
(http://www.diva-portal.org/smash/get/diva2:1110776/FULLTEXT01.pdf)

3. Predicting Bitcoin index with Forum's comments
http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0177630#sec003

4. Using TensorFlow
https://nicholastsmith.wordpress.com/2017/11/13/cryptocurrency-price-prediction-using-deep-learning-in-tensorflow/

5. Predicting with Google Search
https://qz.com/1052656/bitcoin-price-google-trends-can-help-you-figure-where-bitcoins-price-is-headed/


**Approach**

This project will focus on time-series analysis. [TO COMPLETE] 
After choosing at least three different approaches for predicting the Ethereum price, I will analyze those and compare their accuracy

**Data**

Our data come from http://coinmarketcap.com. 


I will need to be careful and transparent with the assumptions
As I have daily new data for the Ethereum, I will need to fix a timeframe from the beginning for each prediction. If possible (if weekly or daily prediction for example), I can take that opportunity to iterate the model and improve it

While there are many options to explore in the crypto world when analyzing predictions -- because of the recent massive interest and thus research about it but also the ease of access to data --, I will focus in this project on a comparison with Google Trends and time-series analysis.



### 1. Exploring the past value fluctuations

This part includes: 
- data collection directly from our source (coinmarketcap.com)
- data cleaning (format and columns names) 
- data visualisation (overview of closing prices and volumes fluctuations) 

_Import libraries and retrieve data_

<img src="images/import_lib_2.png?raw=true"/>

<img src="images/head.png?raw=true"/>

Renaming the columns 

<img src="images/rename_col.png?raw=true"/>

_overview of the closing prices and volumes flucuations since 2015_

Importing the Ethereum logo 

<img src="images/logo.png?raw=true"/>

Plotting the values (closing prices and volumes) across time


<img src="images/visuali.png.png?raw=true"/>




### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
