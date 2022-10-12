# Purpose of the Project
The purpose of the project was to collaborate to pull data using an API call to spoonacular to get food data . In this project we created multiple functionsqueried the spoonacular website using the APoonacular API, which involved reading enrollment data for different states and counties.The data was in csv files. we used read_csv function to in the data in a tibble.
We gave an option to pull the recipes for a particular cuisine(which can be passed as an argument) and then used the recipe id to pull the nutrient content for the particular recipe. We further took that data and ran an exploratory data analysis by creating new variables and creating summaries. The data which was pulled didn't have categorical variables so we created those. Finally we were able to take the data and do anlysis using various plots
# Learnings
We created custom functions to which we can pass a variety of arguments to pull the required data. It was challenging to decide what data to pull as we could have done multiple queries. we finalized our data by doing different queries and anlyzing what it returned.We finalized on recipe and the respective nutrition content.
# What we could do differently
We could have compared the data from different cuisines and could have done nutrient anlysis. Alternately we could have listed all the recipes which have a lower sugar content.
# Link to the vignette.
Here is the [link](https://mcartron10.github.io/Stat558_Project2_CartronRao/) to the vignette
