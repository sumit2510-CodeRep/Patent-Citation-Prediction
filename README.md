# Patent-Citation-Prediction
* Every year there are multiple patent published by various companies, those articles are refered and cited by other patents as well. Our goal is to predict if a new patent is published by a company then which company will most likely to cite the patent in their upcoming article based on the topic, company which published the patent and content of the article.
* Citations provide useful insight for technology dissemination processes, as patents are an important medium of invention.
* Relation between innovation happening in organizations and how they are inter-dependent.

## Dataset & Infrastructure

The dataset used is Google Patents dataset.

* Platform - Google Cloud Platform
* 1 master, 3 worker nodes
* standard-m1 instance
* 30 GB Memory
* 8 CPU cores
* Dataset size – 20 million rows (patents from 1976)
* Tables -
  * Patent
  * Patent citation
  * Assignee


## Predictions

* BERT- 
   -  Accuracy score is 84%
   -  F1 score is 0.8
   -  Precision score is 84%
   -  Recall score is  0.8
* Multilayer Perceptron-
   -  Accuracy score is 72.7%
   -  F1 score is 0.77
   -  Precision score is 70.27%
   -  Recall score is  0.68
* Decision Tree-
   -  Accuracy score is 67.7%
   -  F1 score is 0.62
   -  Precision score is 60.27%
   -  Recall score is  0.677
* Random Forest-
   -  Accuracy score is 77.47%
   -  F1 score is 0.75
   -  Precision score is 85.24%
   -  Recall score is  0.77 
* Naïve Bayes– 
   -  Accuracy score is 12.54%
   -  F1 score is 0.097
   -  Precision score is 14.31%
   -  Recall score is  0.12

## Other Contributors

- Achint Sharma
- Simron Waskar
- Zexu Li 


## Conclusion

* Technology diffusion exists and has been increasing year by year.
* IBM & Samsung are the top most innovation hub in the last decade.
* We can predict the citation by an organization with certain accuracy for top 100 companies.
* The topics extracted from documents show that technology trends are highly reflected in the abstracts/titles.


