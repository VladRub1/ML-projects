# RecSys

This project implements an **end-to-end algorithm for a recommendation system** 
for _music recommendations_.

Simple **memory-based approaches** and a **Latent Factor Model (LFM)** are 
used for candidate selection. **Gradient Boosting** from **[CatBoost](https://catboost.ai/)** 
is used for **re-ranking** among the candidates.

Additionally, the work includes a _comparison of different algorithms for recommendations_ 
and handling _compressed sparse matrices_ for storing information about 
user-item interactions.

Examples of different models in action are also provided.

### Contents:
* [recommendations-project-RubanovVladislav.ipynb](./recommendations-project-RubanovVladislav.ipynb): 
the project
* [music_dataset.csv](./music_dataset.csv): data (information about user-item interactions)
* [tracks_info.csv](./tracks_info.csv): information about music tracks
