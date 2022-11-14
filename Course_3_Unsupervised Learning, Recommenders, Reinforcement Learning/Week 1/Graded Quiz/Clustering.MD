## Question 1
<span style="color:green">**Which of these best describes unsupervised learning?**</span>

        A form of machine learning that finds patterns using labeled data (x, y)

    [ANS] => A form of machine learning that finds patterns using unlabeled data (x). 

        A form of machine learning that finds patterns without using a cost function.

        A form of machine learning that finds patterns in data using only labels (y) but without any inputs (x) . 
## Question 2
<span style="color:green">**Which of these statements are true about K-means? Check all that apply.**</span>

    [ANS] => If each example x is a vector of 5 numbers, then each       cluster centroid \mu_kμ k is also going to be a vector of 5 numbers.

        The number of cluster centroids \mu_kμ k is equal to the number of examples. 

    [ANS] => The number of cluster assignment variables c^{(i)}c(i) is equal to the number of training examples.

    [ANS] => If you are running K-means with K=3K=3 clusters, then each c^{(i)}c(i) should be 1, 2, or 3.  
## Question 3
<span style="color:green">**You run K-means 100 times with different initializations. How should you pick from the 100 resulting solutions?**</span>

        Pick randomly -- that was the point of random initialization

    [ANS] => Pick the one with the lowest cost J

       Average all 100 solutions together. 

        Pick the last one (i.e., the 100th random initialization) because K-means always improves over time 
## Question 4
<span style="color:green">**You run K-means and compute the value of the cost function J(c^{(1)}, …, c^{(m)},\mu_1, …, \mu_K)J(c(1),…,c(m),μ1,…,μK) after each iteration. Which of these statements should be true?**</span>

        Because K-means tries to maximize cost, the cost is always greater than or equal to the cost in the previous iteration.

    [ANS] => The cost will either decrease or stay the same after each iteration.

        There is no cost function for the K-means algorithm.

        The cost can be greater or smaller than the cost in the previous iteration, but it decreases in the long run.
## Question 5
<span style="color:green">**In K-means, the elbow method is a method to**</span>

        Choose the best random initialization

        Choose the best number of samples in the dataset

    [ANS] => Choose the number of clusters K

        Choose the maximum number of examples for each cluster

Copyright ©️ by [Danial](https://github.com/danialcodes) 💖   