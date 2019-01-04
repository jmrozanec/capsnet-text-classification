# capsnet-text-classification
Provides a capsnet implementation for text classification

We provide the following notebooks:
 - dataset-to-embeddings.ipynb: to transform headlines to embedding vectors used as new dataset to perform classification
 - dataset-analysis.ipynb: to obtain general information regarding the dataset: most frequent terms, which cannot be represented as embeddings, most frequent words particular to a specific topic, etc.
 - XGBoost.ipynb: classification performed with XGBoost
 - ConvRec.ipynb: ConvRec implementation and dataset classification
 - CapsNet.ipynb: CapsNet implementation and dataset classification

Results we obtained:


|Metric|CapsNet|XGBoost|ConvRec|
|------|-------|-------|-------|
|Accuracy|0.8901|0.8179|0.8897|
|Time trained|920 minutes|23 minutes|189 minutes|
