# Ensuring Consistent Transactions in a Web Service Environment with Prediction-Based Performance Metrics

Repository containing all the LaTex code associated with the publication.

## Authors

* John T. Ravan III, University of South Carolina, Columbia, SC, 29208 Email: [jravan@email.sc.edu](mailto:jravan@email.sc.edu)
* Shankar M. Banik, The Citadel, The Military College of South Carolina, Charleston, SC, 29409 Email: [shankar.banik@citadel.edu](mailto:shankar.banik@citadel.edu)
* Csilla Farkas, University of South Carolina, Columbia, SC, 29208 Email: [farkas@cse.sc.edu](mailto:farkas@cse.sc.edu)

## Abstract

In this paper, we propose transaction scheduling for web service database transactions.  Our solution ensures consistency 
while preserving efficiency. We propose a prediction-based metric that promotes transactions with reliable reputations based 
on the transactions’ performance metrics. Performance metrics are based on the transactions’ likelihood to commit and their 
execution time. We propose a customized lock management solution to guarantee execution consistency in concurrent web service 
environments. We formally prove that our solution guarantees consistent execution history of concurrent web transactions and 
increases concurrency and performance over traditional locking methods. We developed a simulation using a multi-threaded 
approach.  We generated sample workloads of simulated concurrent transactions over seven tests. Our results show that the 
solution works comparatively with traditional locking and no-locking solutions with the added benefit of ensured consistency 
in some cases and deadlock avoidance in others.

## IEEE Publication Location

[https://ieeexplore.ieee.org/document/9001256](https://ieeexplore.ieee.org/document/9001256)
