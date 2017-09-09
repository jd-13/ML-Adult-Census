This notebook uses US census information to attempt to predict whether an individual earns more or less than $50k.  

The data used can be found here: https://www.kaggle.com/uciml/adult-census-income  

### Overview
A rough outline of the steps taken is as follows:  

1. Visualize the data to identify trends and artifacts that my affect later processes
2. Prepare the data (train/test split, scaling, one-hot encoding, etc)
3. Grid search on several models to identify which will most likely be successful
4. Visualise the performance of the models to better understand shortcomings and areas for improvement
5. Continue to tune the most promising models
6. Test the predictions on the test set
