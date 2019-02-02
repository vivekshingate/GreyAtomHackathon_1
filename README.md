# GreyAtomHackathon_1

### Team Members :
***
<div class="alert alert-success">
  <strong></strong>
  <li><p> Vivek Shingate</p></li>
  <li><p> Kailas D.</p></li>
  <li><p> Akshay Lakade</p></li>
          
</div>



### Use Case :
***
A leading affiliate network company from Europe wants to leverage machine learning to improve (optimise) their conversion rates and eventually their topline. Their network is spread across multiple countries in europe such as Portugal, Germany, France, Austria, Switzerland etc. Affiliate network is a form of online marketing channel where an intermediary promotes products / services and earns commission based on conversions (click or sign up). The benefit companies sees in using such affiliate channels is that, they are able to reach to audience which doesn’t exist in their marketing reach. The company wants to improve their CPC (cost per click) performance. A future insight about an ad performance will give them enough headstart to make changes (if necessary) in their upcoming CPC campaigns. In this challenge, you have to predict the probability of whether an ad will get clicked or not. 

### Data Set
***
https://drive.google.com/file/d/1oJCM7LJ5oCcI4PuQH6vTFypAzwsMA0Jz/view?usp=sh
aring

### Data Description
***
You are given three files to download: train.csv, test.csv and sample_submission.csv Variables
in this data set are anonymized due to privacy.
The training data is given for 10 days ( 10 Jan 2017 to 20 Jan 2017). The test data is given for
next 3 days.


### Features Given
***
- ID (Unique ID
- datetime (timestamp
- siteid 
- website id
- offerid (offer id {commission based offers})
- category (offer category)
- merchant (seller ID)
- countrycode (country where affiliates reach is present)
- browserid (browser used)
- devid (device used)
- click (target variable)

### Evaluation Metric :
***

Submission will be evaluated based on AUC-ROC score. Higher the better.
