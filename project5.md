## Fake Review Prediction 
<img src="images/yelp.gif?raw=true"/>

**Project description:** 
With the higher penetration of internet worldwide comes the rise of ecommerce. More businesses, online or brick and mortar , are using customer's reviews to stand out from the competition. More consumers are also relying on online reviews for purchase decision making.
<br>
With online reviews getting more popular, reviews are becoming a tool whereby business seeks to improve sales. Business can also be targeted with fake review to tarish the reputation.
<br>
This project aims to train a machine learning classifier model to predict whether a review posted on Yelp is recommended/spam/genuine or not recommended/ham/fake. This should give insights on some features of a spam/fake/not recommended review.

### Data

Please refer to http://shebuti.com/collective-opinion-spam-detection/

### Conclusions

Restuarants are willing to pay to buy machine-generated / human written reviews which looks very much like genuine reviews to boost their reputation online. Based on review text alone, its not sufficient to determine which review are spam or genuine.
From the model, some review features like polarity, subjectively, compound and difference in rating from the restaurant's average rating is important. Fake reviews tend to be more polarized. Fake reviewers would also give ratings that are on the extreme scale to make an impact to the business repution.
<br>
User's behvaior is critical to make this prediction. Fake reviewers are generally lower lifetime, post more reviews in a short time and the rating given are generally deviated from the average rating of restaurant.
<br>
For genuine users who have their reviews flagged out frequently, they should try to post reviews that are more objective and avoid posting multiple reviews on the same day.
<br>
This model involves studying user's behavior and its challenges lies in predicting single review users and new users.


[Code](https://github.com/tayjx1987/Capstone)
