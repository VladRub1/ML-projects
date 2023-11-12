# Metric Learning

A project focused on **training custom metrics** based on **Mahalanobis distance**:
* **NCA** (Neighborhood Components Analysis),
* **LMNN** ( Large Margin Nearest Neighbor Metric Learning), 

as well as selecting known metrics:
* Minkowski (L_1 and L_2)
* Chebyshev
* Mahalanobis
* Cosine

for **metric methods of classification** in tasks with **limited datasets** 
(determining the author of a painting).

Additionally, the work examines other improvements to the **kNN algorithm** for 
classification:
* selection of weight functions
* speeding up metric calculation using a linear operator

A **comparison** is also made between the performance of _classic ML models 
for classification_ and _gradient boosting on decision trees_
([CatBoost](https://catboost.ai/)).

[Data used](https://www.kaggle.com/delayedkarma/impressionist-classifier-data) 
include **embeddings** of images obtained using a **convolutional classifier**, 
from a dataset of paintings by famous impressionists.

### Contents:
* [metric-learning-project-RubanovVladislav.ipynb](./metric-learning-project-RubanovVladislav.ipynb): 
the project
* [embeddings](./embeddings): data.
