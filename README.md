# Natural-Language-Processing- Amazon Review

Amazon Reviews: This dataset contains around 35 million reviews from Amazon spanning a period of 18 years. It includes product and user information, ratings, and the plaintext review

# Data Format

product/productId: asin, e.g. amazon.com/dp/B00006HAXW
product/title: title of the product
product/price: price of the product
review/userId: id of the user, e.g. A1RSDE90N6RSZF
review/profileName: name of the user
review/helpfulness: fraction of users who found the review helpful
review/score: rating of the product
review/time: time of the review (unix time)
review/summary: review summary
review/text: text of the review

# Text Data Processing

There are many tactics in Text Data Processing, such as:

a.)Remove non-alphanumeric characters, except for white space.
b.)Convert all characters to lowercase, in order to treat the words such as “Hello”, “hello”, “HELLO”, “HEllO” all the same.
c.)Consider Tokenization, Stemming, and lemmatization.
d.)In addition to clean dataset, we must represent text as a vector of “number” in order to satisfy the requirement since machine learning models always take numeric values as input.


