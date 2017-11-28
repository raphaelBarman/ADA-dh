- spark
- conda install -c conda-forge findspark 
- pip install pyspark_dist_explore

Following data:

- http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Baby.json.gz
- http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/meta_Baby.json.gz
- http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Grocery_and_Gourmet_Food.json.gz
- http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/meta_Grocery_and_Gourmet_Food.json.gz
- http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Automotive.json.gz
- http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/meta_Automotive.json.gz

Need to merge files together, from command line:
- cat reviews_Automotive.json reviews_Baby.json reviews_Grocery_and_Gourmet_Food.json > reviews_auto_baby_grocery.json
- cat meta_Automotive.json meta_Baby.json meta_Grocery_and_Gourmet_Food.json > meta_auto_baby_grocery.json


Alternate data, bigger, so not very useful?
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Electronics.json.gz
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/meta_Electronics.json.gz

