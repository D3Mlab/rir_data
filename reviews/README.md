



# Yelp Reviews


## 50_restaurants_all_rates.csv

yelp reviews from 50 restaurants in our dataset

### Columns
- business_id: id of the restaurant
- user_id: id of the user
- review_stars: rating of the review
- review_text: text of the reviews
- name: name of the restaurant
- categories: restaurant categories such as "Ramen, Noodles"
- date: date of user writing the review


## .pkl files

These files are reviews embedded by BERT and TASB language model. The code uses these files to compute similarity for least similar and most similar sampling method for contrastive learning. So the embedding have been cached in these files to avoid computing them in each run.
