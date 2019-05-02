# Coursera-Reviews-Analysis
It is a Natural Language Processing Problem where we have to decide the sentiments of the users who reviewed the course. and then classifying the reviews into positive and negative.

# Context
This dataset was used for my undergraduate research. The main problem in this dataset is its imbalanced nature.

# Content
I scraped the website of Coursera and pre-labelled the dataset depending on their rating. For a 5-star rating, the review was labelled as Very Positive, Positive for 4-star, Neutral for 3-star, Negative for 2-star, and Very Negative for 1-star. There are 2 files, reviews.tsv and reviews_by_course.tsv. The reviews.tsv file has no grouping, just the course reviews and their corresponding label. For the reviews_by_course.tsv, they are grouped by the CourseId column.

reviews.tsv
Id - The unique identifier for a review.

Review - The actual course review.

Label - The rating of the course review.

reviews_by_course.tsv
CourseId - The course tag. This is in the URL of the course in the Coursera website. For example, in this URL, machine-learning would be the course tag.

Review - A review in a specific course.

Label - The rating of the course review.

# About
Coursera is an online learning platform founded by Stanford professors Andrew Ng and Daphne Koller that offers courses, specializations, and degrees. Wikipedia
Founded: 2012
CEO: Jeff Maggioncalda
Headquarters: Mountain View, California, United States
Employees: 280 (June 2018)
Number of employees: 280 (June 2018)
Founders: Andrew Ng, Daphne Koller
