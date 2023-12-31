# Bookstore_dataset
given the bookstore dataset, we have analyzed and developed a classification model.

# Data Description:
* authors: Author(s) (list of str)
* bestsellers-rank: Bestsellers ranking (int)
* categories: Categories. Check authors.csv for mapping (list of int)
* description: Description (str)
* dimension-x: Dimension X (float in cm)
* dimension-y: Dimension Y (float in cm)
* dimension-z: Dimension Z (float in mm)
* edition: Edition (str)
* edition-statement: Edition statement (str)
* for-ages: Range of ages (str)
* format: Format. Check formats.csv for mapping (int)
* id: Unique identifier (int)
* illustrations-note:
* image-checksum: Cover image checksum
* image-path: Cover image file path
* image-url: Cover image url
* imprint:
* index-date: Crawling date (date)
* isbn10: ISBN-10 (str)
* isbn13: ISBN-13 (str)
* lang: List of book's language(s)
* publication-date: Publication date (date)
* publication-place: Publication place (id)
* rating-avg: Rating average 0-5
* rating-count: Number of ratings
* title: Book's title (str)
* url: Relative url (https://bookdepository.com + url)
* weight: Weight (in kgr)

# Classification Problem: 1

## Rating Prediction:

### Approach:
- After doing some EDA and preprocessing, we did feature extraction - in which we created a new column for discrete values of ratings in the span of 0.5 from 0 to 5. Then we used different multi-class classification models to classify the estimated rating for the new instances.

# Classification Problem: 2

## Weight Prediction
- While taking into the consideration of dimention of the book, we came up with the idea of weight of the book. By which we can predict if the book is over-weight or under-weight. Which is a binary classification problem. We have done this using multiple predicting models like random forest, ridge classification and logistic regression.


## Contributions:
1. EDA:
* Dhruvil Thakor(202101462)

2. Rating prediction:
* Dhruvi Gohel(202101188)
* Varun Vyas(202101468)

3. Weight Prediction:
* Ayush Patel(202101439)
* Aayush Patel(202101452)  
* Dhruvil Thakor(202101462)
