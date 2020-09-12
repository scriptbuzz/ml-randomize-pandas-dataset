# ml-randomize-pandas-dataset

Randomaly shuffle rows in a Pandas dataframe in preperation for training and testing ML models

Sometimes the dataset may contain adjacent groups of rows that share common properties. In some scenarios, such as time series datasets, this is normal. But in other scenarios, this may throw off the model training process. In those cases, we may wish to shuffle the rows in the dataset before we segment the data for the purpose of training, testing, and validation. 


