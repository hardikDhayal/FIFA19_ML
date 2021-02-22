# FIFA19_ML
Analyzing, Visualizing and Training of FIFA19 Dataset.



Sport analytics as a branch is getting more and more recognition for the improvement of all physical sports ranging from football to cricket to basketball to athletics. 
We now have vast repositories of statistics and data points all over the internet which has made it possible to find intricate details that could help the individuals or the teams as whole to get better.
One of such data repository is the FIFA19 dataset which could potentially provide a ton of new information through proper analysis. The analysis could help the coaches, the managers, the players with their plans and serve as an interesting insight for the fans around the globe.
Proper Visualization and Learning is required to extract all the insights from the Dataset, and that is the aim of this project.





The basic outline of the project is as follows:
1.	Reading the Data: Creating a pandas DataFrame which forms the base for all other operations to be done over it.
•	head and describe functions to get a bigger picture and understand the range of values of the data entries.

2.	Dealing with unnecessary features and missing value:
•	Check for missing values in columns where missing values is more than half of the total number of values and Dropping column based on this condition.
•	Filling the missing value for the continuous variables for proper data visualization.

3.	Plotting of graphs: Graphs like bar plots, Violin plot, polar projections,     scatter plot, count plot using libraries matplotlib,seaborn.

4.	Classification of Players into their Respective position:
•	Remove Missing Values
•	Standardize the data
•	Splitting data into train and test set
•	Making a Neural network with 2 hidden layers using Keras.
•	Training the data
•	Checking accuracy and other Metrics 	

