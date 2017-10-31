# A study of Amazon's reviews
# Abstract
Have you ever asked yourself if a truly reliable review existed? The internet is full of both hypercritical and uncritical users, which makes it hard to get an idea on a product from its reviews. Is there a way to define clear metrics based on such unreliable material? Trying to clarify this is the goal of our project. In order to do this we will explore the Amazon dataset and try determining the magnitude of the correlation between a product review and its other features - above all the sales - as well as exploring the role that Amazon various features - like the suggestion system and the product categorization - play in this picture.
We will use a dataset of Amazon reviews spanning 18 years in order to answer this question. 
We believe trying to get some insight out of this confused system could help the whole community of Amazon buyers.

# Research questions
Review quality vs. Review quantity. Which of the two metrics is more representative of the product quality and popularity?

Influence of reviewer personality. Is there a trend in a user's review history that allows to consider him to be biased or unbiased?

Brand fidelity/hate. Can a user be biased towards certain brands, giving them only good/bad reviews?

Influence of "also bought..." feature. What's the effect of this feature? Does it rise sales of potentially "bad" product which happen to be associated with "good" product (where "bad" and "good have to be formally defined).

#review / #sales ratio. Does a commercially successful product implies many reviews? What about the inverse relationship?

Product Categorization. Is there a correlation between the product categorization and the reviews quantity/quality? Do generic categories have more reviews than niche categories?
# Dataset
We plan on using the Amazon review dataset. In this dataset, we have all the core relevant information we want:
- A way to track a user through its userid
- The article she reviewed
- The "helpfulness" of the review
- The rating
We can also find from the metadata of the article the brand, the category, the related articles and the sales rank.

The dataset is can also be found under convenient alternative forms, for example a subset containing all users with at least 5 reviews, which could prove to be very useful.
# A list of internal milestones up until project milestone 2
1. Getting familiarized with the cluster environment.
2. Exploring the different variants of the dataset in order to find the one the most convenient for us.
3. Exploring the data in general to find some useful metrics (review per user/product, average ratings per user, etc.).
4. Assess if there is any missing data and if so, find a wind to scrap it.

# Questions for TAa
