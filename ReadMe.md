# IBMHACKCHALLENGE 2020
![intro](https://images.unsplash.com/photo-1480694313141-fce5e697ee25?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

Find detailed project report in https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/IBM%20HACK%20CHALLENGE%20PROJECT%20REPORT.pdf
## Introduction

   Sentiment Analysis (Opinion Mining) is an extremely powerful tool for predictive modelling and analysis. Sentiment Analysis relies on advanced text mining techniques and then performs Natural Language Processing on the texts to predict the latent sentiment or opinion of the text in a given context like analysing movie reviews, restaurant ratings or in this case government response against the backdrop of the coronavirus pandemic.
   
## Prerequisites
   1.IBM Cloud Account(https://cloud.ibm.com)</br>
   2.Twitter Developer Credentials(https://developer.twitter.com/en#)</br>
   3.Create a Mapbox account(https://www.mapbox.com/)
   
Getting access to twitter API: 
Connect to twitter API by creating a developer account and request credentials for access.
Link->https://docs.inboundnow.com/guide/create-twitter-application/

Setting up IBM cloud services: 
Setting up an IBM cloud account in and creating Node Red Cloud Foundry App. Create Cloudant,ElephantSQL,Visual Recognition, Watson Language Translator Services and connect to Node Red app.

Getting MapBox API Credentials
Create a MapBox account,and get the API tokens

## Procedure
### Importing Flows
1.Open Node-red Flow Editor.</br>
2.Go to the top-right menu section and click on the import option.</br>
3.Import the flows from the folder. After importing the flows, if certain nodes are not installed, install all required nodes from the manage palette of the menu section in node red flow editor.</br>
4.Put your corresponding credentials in the Visual Recognition API node, MapBox Access Token node,the Twitter node,the Postgrestor node and the Cloudant nodes.</br> 

### User Interface
   Copy the HTML code from the HTML/CSS folder in the repo(inline CSS)[use only on desktop]</br>
     1.Landingpage.html</br>
     2.News.html</br>
     3.Stats.html</br>
 Copy the HTML code and paste the entire code in the corresponding template nodes in the Main Page flow.
 
 ### Deploying
 1.Once all the Flows have been imported,the API key values inserted in the respective access nodes,and the HTML codes copied into the template nodes.Click on the red deploy button on top right corner of the node red flow editor. 

    
