## Alternating Least Squares (ALS) - Collaborative based filtering

* ALS (Alternating Least Squares) is a matrix-factorization algorithm used for collaborative filtering in recommendation systems.
It is part of Spark MLlib and is designed to work efficiently on large, sparse rating datasets.
* It is part of Spark MLlib and is designed to work efficiently on large, sparse rating datasets. <br>
* The central idea is to represent the sparse user–item rating matrix 
𝑅
R as the product of two low-rank latent factor matrices. Let 
𝑅
∈
𝑅
𝑚
×
𝑛
R∈R
m×n
 denote the matrix of ratings, where 
𝑚
m is the number of users and 
𝑛
n is the number of items.

### What ALS Does

1. ALS takes the user–item rating matrix (users rating books) and breaks it into two smaller matrices: <br> -> User factors <br> -> Item factors
2. These factors represent latent features that describe: <br> -> User preferences <br> -> Item characteristics
3. ALS learns these features by repeatedly minimizing the error between: <br> -> Actual ratings <br> -> Predicted ratings from the factor matrices

### Matrix factorization
Matrix factorization is a technique that decomposes a large matrix into two or more smaller matrices, which is widely used in recommender systems to find hidden patterns in user-item interactions. <br>
steps:
1. Initialize Random
2. Calculate error
3. Lambda ( regularization )
4. next iteration

### Collaborative filtering
Collaborative filtering is a machine learning technique used in recommender systems that predicts user preferences by analyzing past behavior and interactions from a large group of users.
Alternating Least Squares (ALS) algorithm is a widely used model-based collaborative filtering (CF) technique. 
