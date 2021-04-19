# RandomForest
Complete details of Ensemble - Bagging technique - Random Forest along with some examples

Decision Trees: - Causes Overfitting and also High Variance.

- If we only build one tree we would only take advantage of their limited scope of information, but by combining many trees' predictions together, our net information would be much greater.
- Overfitting ocurs when a flexible model memorizes the training data by fitting it closely. Thus causing Low bias and High Variance.

Bagging: - If few features are correlated, model will not get better beyond few trees.

# Random Forest
- Ensemble machine learning technique capable of performing both regression and classification tasks using multiple decision trees and bagging.
- Random forest adds additional randomness to the model, while growing the trees.
  - Random sampling of training observations when building trees
  - Random subsets of features for splitting nodes


- Each individual tree brings their own information sources to the problem as they consider a random subset of features when forming questions.
- Again if ech tree used the same dataset, every tree would be greatly affected by the same way by an anomaly or an outlier.

----------------------------------------------------------------
***In BAGGING : Only Row Sampling***
***In RandomF : Both Row Sampling and Feature Sampling***

In RF each tree sees only a subset of all the features  when deciding to split a node. (max_features = sqrt(n_features))

------------------------------------------------------------------
HYPER PARAMETERS:

