# **Air Pollution Analysis**
Team Magical Ligers!<br>
Go Team! <br> 
![magicalliger](./annual_seasonal_notebooks/images/ml.jpeg "Magical Ligers")
## **Project 1**
**Team:** Magical Ligers<br>
**Team Members:** Hyun Soo Kim, Nazia Haque, Wayne Tseng, Christian Pompa

## **Project Description:** 
* Air Pollution data on: 
    * Population & Location ( Hyun Soo Kim )
    * Seasons: summer spring, holiday weekends ( Christian )
    * Time of Day (Christian)
    * Twitter data, by location about air pollution. ( Naz )
    * Twitter & Covid-19 (Naz)
    * How much pollution do cars give off? Which brand of car? ( Wayne )

## **Research Questions Interested in Exploring:**
### Seasons

* Should the US start wearing masks after a pandemic?
* How long are we living in moderate and good conditions for air quality?
* Does it really matter to the US population? 
* How are we polluting cities? 
* Which region contributes to air pollution?

### Time of Day
Measurements by the day, and hour, can provide the percentage of time we live in good or neatrual air. Which time of day provided the worst air pollution? <br>

### How healthy is healthy?
Every time frame includes sample measurements. EPA.gov has listed the PM 2.5 health index which informs us the severity levels in air pollution. Combining measurements with specific thresholds can give us answers on "How bad is bad?"<br>

### Social Media data, by location about air pollution (Covid): 
Twitter API was used to gather social media information for the US only.  CA citizens tweet the most about air pollution, followed by NJ, NY, and TX.  NJ & NJ have Ozone-Polluted Cities.  CA has the most cities with bad air pollution. So, the awareness is evident in these states in particular. After analyzing the count of tweets per state.  We created a Word Cloud plot which tells us the frequency of words used in the tweets, by their size scale.  What was surprising is that covid-19 and coronavirus actually had a pretty high frequency in relation to the air pollution tweets.  Using the data pulled for air pollution tweets, we then pulled tweets related to covid-19 and coronavirus.  There were a number of tweets where people were posting about how clear the air is and also posting articles that link to research that say the higher the air pollution is in an area the higher the death rates are due to the virus. CA had the most tweets followed by NJ, NY, and MA.  Some of the articles came from Harvard research so that is why MA probably has more tweets about this subject.  All in all the US population does care about air pollution, some do more than others due to the air pollution affecting where they live.  <br>

### Cities with subways/train public transit
Information coming soon. <br> 

### How much pollution do cars give off? Which brand of car?
Information coming soon. <br> 

### Population of Top 5 major cities
Information coming soon. <br> 

## **Datasets Required:**
List all dataset urls, excel files, etc. Add documentation if available.
* AQS EPA.GOV: Air Pollution API. Retrieves air pollution data needed.<br>
Ex api: https://aqs.epa.gov/data/api/list/states?email=test@aqs.api&key=test <br>
Documentation: https://aqs.epa.gov/aqsweb/documents/data_api.html 
* Twitter<br>
Ex api: https://developer.twitter.com/en  <br>
Documentation:https://developer.twitter.com/en/docs/tweets/post-and-engage/api-reference/post-statuses-update
Library: http://docs.tweepy.org/en/latest/
* Population Data
https://www.census.gov/content/census/en/data/tables/time-series/demo/popest/2010s-counties-total.html
