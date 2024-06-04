# CryptoClustering
Import required libraries and dependencies.
Load the data into a Pandas DataFrame and make the index the "coin_id" column.
Generated a summary statistics.
Prepared the Data; Used the `StandardScaler()` module from scikit-learn to normalize the data from the CSV file.
Created a DataFrame with the scaled data.
Copied the crypto names from the original data.
Set the 'coinid' column as index.
Found the Best Value for k Using the Original Scaled DataFrame.
Plotted a line chart with all the inertia values computed with the different values of k.
Found that 4 is an optimal value of K.
Initialized, Fit, and made predictions using 4 for the number of clusters as well as the scaled data. 
Created a copy of the DataFrame and added a new column. 
Visualized the data using scatterplot. 
Created a PCA model instance.
Retrieved the explained variance. 
Found the Best Value for k Using the PCA Data.
Visualized the data using a scatter plot, hvPlot.
Determined the Weights of Each Feature on each Principal Component by creating a dataframe and using the columns from the original scaled DataFrame as the index. - I was having trouoble with this part of the challenge and could not figure it out on time. 

My resources: 
Past activities.
Tutor.
TA's
Chat gpt
