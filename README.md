# Foodie - recipes recommendations

## Project goal and overview
Ok, so hello DS community! That's my very first data science project I wanted to share with you. This is a food recipe recommendation tool - based on item similarity machine learning tool - cosine similarity. The user passes an existing recipe to the ML model and gets list of most similar recipes that he should like. <br/>
The model uses data shared as a dataset by Food.com (formerly GeniusKitchen). The data used in the model consists of:
 - Raw data of the recipes - that's where the original recipe is stored - in text format,
 - List of interactions between users and particular recipes - review and rate given by a user to a particular recipe.

There are also other data imported, which may be used in other cases.
After the data was imported it was analysed to let us know what we are dealing with. To make it easier I've gathered data from imported files in one dataset. I used it then to create rankings of the most popular recipes, recipes with highest ratings, or distribution of interactions number among the recipes.<br/>
<br/>
<img src="output/output1.png" alt="Ranking_1" width="500">
<br/>
<br/>
<img src="output/output2.png" alt="Distribution_1" width="500">
<br/>
<br/>
After that the data was implemented in the ML model using sparse matrix. Having the model ready, the user needs to know what recipes he can base on, so an easy function to search for recipes has been deployed. Using it let's us know what can be used as an input and we get our recommendation!

## But why...?
I treat this project totally edcuational, as it was my first battlefield to work with data management tools:
 - Machine learning (sklearn.metrics.pairwise -> cosine similarity)
 - Pandas,
 - Numpy,

I also used it to train other skills:
 - Creating functions - I know, in some points it could've been done easier way,
 - Using fstrings,
 
So yeah, pretty productive.

## How to run the project
 - Download repo files,
 - Download the datasets from: https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions,
 - Create Conda environment using environment.yml file,

## Possible upgrades
If needed, the project could be upgraded in some areas:
 - User similarity approach could be used,
 - The data could be gathered from web - there are several APIs that provide current data like used here,

## Credits
This project is based on Anime recommendations project found on Kaggle: https://www.kaggle.com/code/yonatanrabinovich/anime-recommendations-project/notebook

Thank you!

