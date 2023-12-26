# ml_product_prediction

What this code about?
This code will train a model for next product likely to purchase by user, given user behaviour and interaction data.
 
1.The following code will create a model using merged data provided (merged.csv). The output of the training will be saved as collab_filtering_model.pkl.

2.The data used for training is (merging.vsc) , which is  merging of 3 files (product_details, purchase_history_customer_interactions), as a flat csv file to be used by ML model training.

2.ML Algorithm: Due to small amount of data had, and understanding the features/columns on the data, the algorithm used is collaborative filtering using SVD (Singular Value Decomposition).

3. Deep learning is not possible in this case (amount of data), to get more accurate prediction might be possible using Deep Learning (RNN/LSTM) if more data provided.

How to Run?
This code is created and run using google colab. You can use the same environment to run this code.




