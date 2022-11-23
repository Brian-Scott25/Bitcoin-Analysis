# Bitcoin-Analysis
### Author: Brian Scott and Jason Thomas, CPA

#### General RPubs Link: https://rpubs.com/BrianScott
This link is to my entire R Pubs account, the specific links to each markdown will be posted below.

## Project Purpose

The focus of this project is to aid in investment strategies for Cryptocurrency traders. We intend to use statistical procedures to determine potential future prices, stop loss levels, and optimal points of entry. The primary objective is to accuratly determine BTC's percentage price change, in terms of direction, over a one week period. The goal in question alligns well with  a machine learning technique like classification or standard logitstic regression (Both are similar in many aspects), but to be thorough an OLS estimation model was produces as well. 

The intention is to create several models based on different creation approaches to find the model most suitable for traders. The models to be designed are: regression for point estimate predictions, logtistic regression, and machine learning techniques such as classification and clustering. 

## OLS Prediction Model For BTC
The goal of this model is to determine BTC's closing price one week in the future, along with the directional change in price for BTC. I have added the R Markdown to the repository, and posted below is the link to the my RPubs account for this specific file. Although a logit or pobit model would be better suited for the direction question, I analyzed both directional change and point estimate accuracy in this script. I intend to post a logit model markdown soon.

The OLS Prediction results indicate a very high accuracy, but it does not catch the directional change very well. Which means the model is insufifient for practical use. As stated above, this seems to be another indication that OLS is the wrong approach for this project.


#### RPubs Link: https://rpubs.com/BrianScott/959165
