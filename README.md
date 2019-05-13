# Node-RED Twitter Workshop
These Node-RED flows use Twitter to introduce a variety of Node-RED visual programming techniques and simple ways to use the powerful Watson Cognitive services.


These Twitter Node-RED recipes showcase:
* A simple flow that watches a Twitter feed.
* Perform Sentiment analysis of Tweets. You could retweet positive tweets or SMS tweets to your friends
* Perform Tone analysis of Tweets using the [Watson Tone Analyzer](https://console.bluemix.net/docs/services/tone-analyzer/getting-started.html#getting-started-tutorial) service
* Speak Tweets using the [Watson Text to Speech](https://console.bluemix.net/docs/services/text-to-speech/getting-started.html#gettingStarted) service
* Store Tweets and Sentiment scores in a [Cloudant database](https://console.bluemix.net/docs/services/Cloudant/getting-started.html#getting-started-with-cloudant) for historical analysis
* Build a Node-RED Dashboard that charts Twitter hashtag sentiment history
* Perform Image analysis of pictures attached to Tweets using the [Watson Visual Recognition](https://console.bluemix.net/docs/services/visual-recognition/getting-started.html#getting-started-tutorial) service
* Build a Nutrition Image Analysis dashboard to report the ingredients and nutritional information from the [USDA](https://ndb.nal.usda.gov/ndb/doc/index#)
  * Tweet a picture of food and use the [Watson Visual Recognition](https://console.bluemix.net/docs/services/visual-recognition/getting-started.html#getting-started-tutorial) custom [food classifier](https://www.ibm.com/blogs/bluemix/2017/05/watson-learns-see-food-introducing-watson-visual-recognition-food-model/). Great fun!

You might want to learn from the Node-RED Twitter workshop that I wrote to teach Node-RED and Watson Cognitive services.
*Follow the step-by-step instructions* to create all of these example [flows](/flows).

If you're interested in trying these Node-RED recipes, find them [here](/flows):  

Scroll down in this README to preview [screenshots](/screenshots) of the Node-RED flows.

With a little bit of Node-RED Dashboard magic, you can create Dashboards that look like this:
![Nutrition Twitter Dashboard Screenshot](/screenshots/Node-RED-Twitter-TweetNutritionAnalyzer-Dashboard.png?raw=true "Nutrition Twitter Image Analyzer Dashboard")

## Node-RED flows in this repository:
---
### A simple flow that watches a Twitter feed

![Simple Twitter flow](/screenshots/Node-RED-Twitter-TweetSimple.png?raw=true "Simple Twitter flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-Simple.json">Node-RED flow to watch a Twitter feed</strong></a>
</p>

---
### Perform Sentiment analysis of Tweets

Search for positive or negative tweets. You could retweet positive tweets or SMS tweets to your friends.
![Sentiment Twitter flow](/screenshots/Node-RED-Twitter-TweetSentiment.png?raw=true "Sentiment Twitter flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-Sentiment.json">Node-RED flow that performs Sentiment analysis of Tweets</strong></a>
</p>

---
### Perform Tone analysis of Tweets using the Watson Tone Analyzer service

![Watson Tone Analyzer Twitter flow](/screenshots/Node-RED-Twitter-TweetTone.png?raw=true "Watson Tone Analysis Twitter flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-Tone.json">Node-RED flow to perform Tone analysis of Tweets</strong></a>
</p>

---
### Speak Tweets using the Watson Text to Speech service.

![Watson Speech to Text Twitter flow](/screenshots/Node-RED-Twitter-TweetSpeak.png?raw=true "Watson Speech to Text Twitter flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-Speaker.json">Node-RED flow to Speak Tweets</strong></a>
</p>

---

### Store Tweets in a Cloudant database for historical analysis
. Download the [flow](/flows/Tweet-Store.json)
![Store Tweets in Cloudant flow](/screenshots/Node-RED-Twitter-StoreTweet.png?raw=true "Store Tweets in Cloudant flow")

<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-Store.json">Node-RED flow to Store Tweets</strong></a>
</p>

---
### Build a Node-RED Dashboard that charts Twitter hashtag sentiment history

![Twitter Sentiment History Dashboard Screenshot](/screenshots/Node-RED-Twitter-TweetSentiment-Dashboard.png?raw=true "Twitter Sentiment History Dashboard")

![Twitter Dashboard flow](/screenshots/Node-RED-Twitter-TweetDashboard.png?raw=true "Twitter Sentiment History Dashboard flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-Dashboard.json">Node-RED Dashboard flow that charts Twitter sentiment</strong></a>
</p>

---
### Perform Image analysis of pictures attached to Tweets using the Watson Visual Recognition service

![Twitter Image Analysis Dashboard Screenshot](/screenshots/Node-RED-Twitter-TweetImageAnalyzer-Dashboard.png?raw=true "Twitter Image Analyzer Dashboard")

![Watson Visual Recognition Image Analysis Twitter flow](/screenshots/Node-RED-Twitter-TweetImageAnalyzer.png?raw=true "Watson Visual Recognition Image Analysis Twitter flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-VisualRecognition.json">Node-RED flow to perform image analysis of pictures attached to Tweets</strong></a>
</p>

---
### Plot location of Tweets on a Map

![Mapbox WorldMap Twitter Dashboard](/screenshots/Node-RED-Twitter-TweetWorldMap-Dashboard.png?raw=true "Node-RED Mapbox WorldMap Dashboard")
![Mapbox WorldMap Twitter flow](/screenshots/Node-RED-Twitter-TweetWorldMap.png?raw=true "Node-RED Mapbox WorldMap flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-WorldMap.json">Node-RED flow to plot Tweet locations</strong></a>
</p>

---
### Build a Call for Code Natural Disaster Twitter Analyzer

Combine all of the flows in this tutorial into one dashboard that could be used as part of a Call for Code Natural Disaster Response application that listens to Tweets from survivors who mark themselves safe.

![Call for Code Safe Twitter Dashboard](/screenshots/Node-RED-Twitter-TweetCallforCode-Dashboard.png?raw=true "Node-RED Call for Code Safe Dashboard")
![Call for Code Safe Twitter flow](/screenshots/Node-RED-Twitter-TweetCallforCode.png?raw=true "Node-RED Call for Code flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-CfCSafe.json">Node-RED flow to plot Tweet locations of Safe Survivors</strong></a>
</p>

---

### Build a Nutrition Image Analysis dashboard

Build a Nutrition Image Analysis dashboard to report the ingredients and nutritional information from the USDA.

![Nutrition Twitter Dashboard Screenshot](/screenshots/Node-RED-Twitter-TweetNutritionAnalyzer-Dashboard.png?raw=true "Nutrition Twitter Image Analyzer Dashboard")

![Nutrition Food Image Analysis Twitter flow](/screenshots/Node-RED-Twitter-TweetNutritionAnalyzer.png?raw=true "Nutrition Food Image Analysis Twitter flow")
<p align="center">
  <strong>Get the Code: <a href="flows/Tweet-NutritionAnalyzer.json">Node-RED Dashboard flow to perform image analysis of food Tweets</strong></a>
</p>

---
