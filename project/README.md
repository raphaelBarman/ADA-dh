# A study of Amazon's reviews
# Abstract
Have you ever asked yourself if a truly reliable review existed? The internet is full of both hypercritical and uncritical users, which makes it hard to get an idea on a product from its reviews. Is there a way to define clear metrics based on such unreliable material? Trying to clarify this is the goal of our project. In order to do this we will explore the Amazon dataset and try determining the magnitude of the correlation between a product review and its other features - above all the sales - as well as exploring the role that Amazon various features - like the suggestion system and the product categorization - play in this picture.
We will use a dataset of Amazon reviews spanning 18 years in order to answer this question. 
We believe trying to get some insight out of this confused system could help the whole community of Amazon buyers.

# Research questions

Question 1:
Review quality vs. Review quantity. Which of the two metrics is more representative of the product quality and popularity?

Question 2:
Influence of reviewer personality. Is there a trend in a user's review history that allows to consider him to be biased or unbiased?

Question 3:
Brand fidelity/hate. Can a user be biased towards certain brands, giving them only good/bad reviews?

Question 4:
Influence of "also bought..." feature. What's the effect of this feature? Does it rise sales of potentially "bad" product which happen to be associated with "good" product (where "bad" and "good"have to be formally defined).

Current answer:
We started by focusing on the "bought together" feature because it is deeply correlated to the "also bought" feature. The reason for this correlation is easy to see: if the user is influenced by the "also bought" feature, then he'll buy the featured object along with the one he's currently visualizing.
We found out that often product with very different ranking are bought together, which hints at the possibility that popular (="good") products may indeed increase the sales of unpopular (="bad") projects.
We need to further delve into the data to draw more conclusions.


Question 5: #review / #sales ratio. Does a commercially successful product implies many reviews? What about the inverse relationship?

Current answer:
By analyzing the data we didn't see a trend that hinted at a correlation between number of reviews and sales of a product.
For example, the product ranked number 1 in the office management category had 1 review, much like the product ranked 2394050 in the automative category. Always in the automative category, the product 2518941 has 20 reviews even if its rank is lower than the one of the product described before, essentially invalidating the hypothesis of a (linear) relationship between number of reviews and sales.
However we still haven't the results from the cluster due to time contrains and cluster overload, which makes this statement formally unrepresentative.

Question 6: Product Categorization. Is there a correlation between the product categorization and the reviews quantity/quality? Do generic categories have more reviews than niche categories?

Current answer:
Our results indeed hints at the existence of general categories with more reviews and niche categories with less reviews.
For example, a general and popular category like 'automotive'  has 17 reviews in our sample dataset, while a niche and obscure categories like 'Power Window Motors'  has 1 review.

# Dataset
We plan on using the Amazon review dataset. In this dataset, we have all the core relevant information we want:
- A way to track a user through its userid
- The article she reviewed
- The "helpfulness" of the review
- The rating
We can also find from the metadata of the article the brand, the category, the related articles and the sales rank.

The dataset is can also be found under convenient alternative forms, for example a subset containing all users with at least 5 reviews, which could prove to be very useful.

# A list of internal milestones up until project milestone 3
1. Develop our answers and go deeper in the analysis, finding out what kind of other questions can be triggered by answering to others
2. Finding some nice visualisation of the data that can be relevant
3. Begin the redaction of our observations for the report


# Questions for TAa
