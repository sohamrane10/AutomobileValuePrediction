Automobile Value Prediction Model
Process:
1.	DATASET: Initially, I considered choosing saved dataset within Microsoft Azure to work upon. I chose Automobile Prices which had raw data.
2.	PRE-PROCESS: This process includes 2 processes namely,
•	Handling missing data values or cleaning data values, which eliminates unnecessary string data that complicates evaluating the model. Specifies how to handle the values missing from a dataset.
•	Encoding Categorical Values, first we select data columns that are supposed to be categorized. Then we adjust settings to “Make categorical”. Selects columns to include or exclude from a dataset in an operation. Formerly known as Project Columns.
3.	SPLITTING DATA: We first “Edit Meta Data” and after that we choose Split data, splitting the data set into two parts: Training Data Set and Testing Data Set. Edits metadata associated with columns in a dataset. Formerly known as Metadata Editor. Split the rows of a dataset into two distinct sets.
4.	ALGORITHMS: Next, we apply regression algorithms on both of our datasets, first we apply BOOSTED DECESION TREE and after that we apply LINEAR REGRESSION.
NOTE: We remove the decision tree because it makes it difficult to evaluate our model. We keep Linear Regression.
5.	HYPER-PARAMETERS: We apply “Tune Model Hyperparameters”, thus adding randomized search and choose default values in the settings. Perform a parameter sweep on the model to determine the optimum parameter settings. Formerly known as Sweep Parameters.
6.	SCORE MODEL: We score both our models. Score a trained classification or regression model.
7.	EVALUATE MODEL: Evaluates a scored classification or regression model with standard metrics.
