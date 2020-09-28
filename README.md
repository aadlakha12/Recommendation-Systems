# Recommendation-Systems

Recommendation Engine which helps to get the similar items to users or items to similar users to recommend.
This Recommendation-Systems is based on collaborative filtering. It has two types user-user filtering and item-item filtering.

#### User-User Filtering

User-user filtering looks for the similarity between every individual user. It’s about the behavior of a user by collecting preferences from many users and can predict for similar user in future. If user A and user B has same preference for some item. It’s likely that they have same preference for other item as well rather than to other user C who has different preferences.

#### Item-Item Filtering

Item-item collaborative filtering, or item-based is an other type of collaborative filtering for recommendation engine based on the similarity between items calculated using user's ratings of those items. Item-item based filtering is considered to be most viable.

Cosine Similarity is used to find the similarity between the objects as similarity measure.

![alt text](https://github.com/aadlakha12/Recommendation-Systems/blob/master/Cosine.png?raw=true)

Mathematically, it measures the cosine angle between two vectors projected in a multi-dimensional space.

As an example we have two sets as following:

A = [2, 1, 1, 2, 1, 0]
B = [1, 1, 1, 1, 1, 1]

We can apply cosine similarity on the above sets as following

Cos(A,B) = (2*2 + 1*1 + 1*1 + 2*1 + 1*1)
√(2*2 + 1*1 + 2*2 + 1*1 + 1*1)*√(2*2 + 1*1 +1*1 +1*1 +1*1 +1*1)
= > 9/9.9498 =0.9045


This is implemented with Book Dataset.

The Book dataset has 3 tables.

• Users
Contains the users. It has three columns User-ID, Location, Age.

• Books 
Contains books detail. Books are identified by their respective ISBN. It has ISBN,Book- Title, Book-Author, Year-Of-Publication, Publisher and URLs.

• Book-Ratings
Contains the book ratings information. Ratings are on a scale from 1-10. Higher values
denoting higher appreciation, otherwise, lower value less appreciation.


 
 
  
