# Content-based recommender


Author: Konrad Jasiński

## Requirements

Python 3.7.9 or higher

Install all necessary packages provided in requirements.txt

With pip:
```
pip install -r requirements.txt
```
With conda:
```
conda install --file requirements.txt
```

## Overview

The goals of the project are:

1. prepare dataset of hotel recommendations for content based recommender,
2. select best features for the model,
3. find the best model for recommending hotels for users,
4. compare the results against Amazon recommender.

Data preparation is done in <code>project_1_data_preparation.ipynb</code>

Defining features, implementing recommender, tunning, and testing the recommender are included in <code>project_1_recommender_and_evaluation.ipynb</code>

### Used algorithms
The best recommender was XGBoostCBUIRecommender.


### Achieved results
Final HR@10 result is 0.061779
