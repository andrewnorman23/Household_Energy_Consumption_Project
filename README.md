# Household_Energy_Consumption_Project

For this project I was given a dataset with a very large amount of variables related to household energy consumption and asked to try to identify some of the key contributors to energy consumption. That dataset is posted under the data folder in a zipped file due to size. It is a real world RECS dataset consisting of 800 variables, of which I chose roughly 20 variables.

First, I cleaned the dataset by selecting the variables from the dataset that I was interested in and converted all the variables to factors since in the documentation they were listed as factors but to start they were integers.

Next, I split the data up into my test and train datasets for my predictive model at the end of my evaluation.

Then I created a detailed graph that plotted the different levels of my variables of interest against total energy usage so I could see if I was correct in my assumptions about how they interact.

After that, I created my LASSO model based off of my dataset splits and arrived at the optimal lambda value for the final model for the remaining data.

Finally, I changed the scaling of the variables that I was interested in to see how that changed with the predicted energy consumption and arrived at the conclusion that all of my predictions were correct based off of the figure that I created to visualize the changes in variables.
