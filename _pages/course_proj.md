---
title: "SFU Master Course Project"
permalink: /course_project/
author_profile: true
---

## CMPT732-Project-YelpRanking
### Introduction:
We build a recommendation system targeted on Yelp new users and Yelp existing users respectively. Regarding the system for yelp new users, new users can input flexible and complicated
keywords such as "Taco Lunch", "Cafe Friends". Then, the website would output restaurants with its reviews matching with the keywords most and high sentiment score.
As for recommendation system for Yelp existing users, they just simply input user ID and the website would output 3 results through item-item similarity, user-item similarity, and friends
social network.

### Recommendation Systems:
**1. Content-Based Recommender:** focus on properties of items. To solve the cold-start problem, we added recommendation by key words search. We feed each word of review into vectors.
    Similarity of items is determined by measuring the similarity in the properties. We use 2 methods of content-based and compare the performance of similarity score through cosine-similarity formula.  <br>
* TFIDF-LDA  (Output topics from the vector of words)
- Word2Vec (Neural network to place similar words together with nearby vextor space)

**2. Item-item similarity:** recommend based on the most similar items found by restaurants' reviwes. These restaurant reviews are selected for restaurants visited by the user before. <br>

**3. User-item similarity:** recommend the restaurants based on similar type of restaurants visited by other users.
* Alternating Least Square (ALS) --Matrix factorization to compose large user/item matrix into lower dimensional user and item factors.

**4. Friends social network:** choose to recommend restaurants as being top ranked by user's friends (4 or 5 stars).

### Github Link:
[Github Link](https://github.com/denisechendd/course_project/tree/master/yelp_recommend)

### Report Link:
[Report Link](https://github.com/denisechendd/course_project/blob/master/yelp_recommend/Yelp_Project_Final_Report.pdf)


## Advanced Deep Learning with Keras in Python

**May, 2019 (DataCamp)**

<img src="/images/Online_certi/certificate_1.jpg" width="80%" height="80%">
