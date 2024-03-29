# RS-project-hw3

## Model Design & Comparison for Recommendation Models

### Task

Model Design and Comparison for Recommendation Models

* Data filtering: remove users whose #interactions < 3
* Data splitting: 5‐Fold Cross Evaluation
  * Test data: Randomly select 20% user‐item interactions
  * Report the average scores of RMSE, Recall, NDCG over 5 testing sets

* Dataset 1: MovieLens 100K
* Dataset 2: Yelp
* Evaluation metrics:
  * RMSE (real‐valued)
  * Recall@10 (binary)
  * NDCG@10 (binary)

### Files

* code:
  * R76114026_UCF-cos.ipynb : User‐based CF [UCF‐c] (cosine as similarity)
  * R76114026_CF-PCC.ipynb : CF [CF‐p] (Pearson correlation as similarity)
  * R76114026_ICF-cos.ipynb : Item‐based CF [ICF‐c] (cosine as similarity)
  * R76114026_FNN.ipynb : FM‐supported Neural Networks [FNN]
  * R76114026_FNN-yelp.ipynb
  * R76114026_My own nn model.ipynb
* report:
  * R76114026_HW3.pdf
