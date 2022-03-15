#  This is Group 5 STA141B Final Project
## Analysis through Disaster Tweets
Link to our project's video Tutorial(https://github.com/WentaoMo/141B-Test/edit/gh-pages/index.md) to watch an interesting video about our final project

Group Member:
Wentao Mo: wmo@ucdavis.edu

Yuyan Fan: (yuyfan@ucdavis.edu)

Ruixin Pang: (rxpang@ucdavis.edu)
 

# System setting up: In progress

```markdown
# Loading constructed project: In Progress 1%
## Loading constructed project: In Progress 5%
### Loading constructed project: In Progress 20%
#### Loading constructed project: In Progress 50%
##### Loading constructed project: In Progress 99%
###### Loading constructed project: In Progress 100%
1. Introduction:
Twitter has become an important communication tool nowadays.

The easy access to smartphones and internet enables people to spread emergency information in real-time.
Because of this, more agencies are interested in programatically monitoring Twitter.

But, it’s not always clear whether a person’s words are actually announcing a disaster. 
Therefore, in this project, 
we will be building a machine learning model to predict which Tweets are about real disasters and which one’s aren’t.

The dataset is from kaggle natural language processing challenging(https://www.kaggle.com/c/nlp-getting-started).

```

```markdown
# Connecting to Agenda: In Progress 1%
## Connecting to Agenda: In Progress 5%
### Connecting to Agenda: In Progress 20%
#### Connecting to Agenda: In Progress 50%
##### Connecting to Agenda: In Progress 99%
###### Connecting to Agenda: In Progress 100%
Reading dataset
Our first step is using pandas to read the dataset.
The data we used is from the kaggle competition- natural languages processing: disaster tweets.

Exploratory data analysis (EDA)
The second thing we will do is exploratory data analysis, which is the initial investigation of the data. 
Since this data set is related to disaster tweets.
we will focus on analyzing these texts on sentence level, word level, and character level. 
Also, we want to make some data visualizations such as word clouds.

Data preprocessing
The third step is data preprocessing. 
In this step, we want to use some NLP techniques we learned in class such as: 
tokenization, stemming, lemmatization and stop word removal. 
This will make our raw data into a more usable and desired form. 

Vectorization
After doing that, we will get a list of tokens. 
Then we will need to transfer them into the vectors that our algorithm can work with. 
(We need to apply cleaned text into this analysis)

Building models
The last step is to build our machine learning models.
We use our statistical model to predict our outcome:
(which are diaster tweets, and which are not)

```
<li><a href="Part1.html">Part I: Reading Data </a></li>
<li><a href="Part2.html">Part II: Data Description</a></li>
<li><a href="Part3.html">Part III: Data Exploration and Visualization</a></li>
<li><a href="Part4.html">Part IV: Basic Data Processing</a></li>
<li><a href="Part5.html">Part V: Data Vectorization</a></li>
<li><a href="Part6.html">Part VI: Statistical Modeling</a></li>
<li><a href="reference.html">Part VI: Reference Page</a></li>

# Conclusion:
```markdown
# Accessing conclusion: Processing 100%
The 3 main goals of our final project is to utilize various techniques we learnt in class to conduct the data analysis, data preprocessing, 
and build a machine learning model to classify if one tweets is reporting a real disaster or not. 

There are several interesting findings within our project.
First of all, we find that no matter the tweet is reporting a real disaster or not, it is more likely to mark the position when it is sent in the U.S. 
In other words, the American users prefer to mark their location when sending a tweet. 

Also, we find that the distribution of sentence numbers, word numbers, 
and character numbers within one tweet are pretty similar no matter it is a disaster tweet or a non-disaster tweet. We also find that the word cloud we produced also share high similarities. 

Besides, we notice that when the texts of tweet containing the proper nouns related to a natural disaster or some adjectives containing dangerous information, 
it is more likely to be classified as a disaster tweet. 
After all the analysis, we cultivate a logistic regression model to classify the disaster tweets. 

```

# You can also view our tutorial video online!
See <b>Video Presentation</b> <a href="https://www.youtube.com/watch?v=nHkSAYiRhe8">here</a>

# Interesting Tour starts here!
<font size="4"><a href="hw5.html">Next Step: Reading Data </a></font>
