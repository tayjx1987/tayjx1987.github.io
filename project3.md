## Web APIs & Classification
<img src="images/parent.png?raw=true"/>

**Project description:** 
Using data obtained from webscraping, to train a classifier to predict which subreddit a given post came from. 

### Data

Data were scraped from www.reddit.com.
<br>
2 subreddit (Parenting and Childfree) were selected and 1000 posts(each) were scraped.

### Conclusions

We had trained a classifier model - Logistic Regression and achieved an accuracy score of 94.1%. However there remains a misclassification rate of 5.9%.
<br>
While machine learning models are able to predict, with great accuracy, the subreddit for the post to be in, we are not able to control users' choice of words(which greatly affect our accuracy).
<br>
For this case, perhaps other NLP techiques(eg, sentimental anaylsis) have to be used in conjuction to improve the accuracy of the classification.


[Code](https://github.com/tayjx1987/Project-3)
