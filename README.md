# 142FinalProject

## Project Status and Future Work
We have currently created and tested multiple models to see which song traits appear in the most popular songs. Of our models the best one seemed to be our random forest, however it would be interesting to continue this project to include songs from more recent years (2020 and 2021) to see if any of our findings develops. As of now, all code is up to date and contains our most recent work along with all the data that was used.


## Code Overview
Our code is currently split into 3 different sections. In the first section, we clean our data using NLP techniques along with merging our original dataset with others such as the Grammy award winners in order to create a dataframe with all the information we need. From there, we limited our search to only include years 1990-2019. This time period was selected because it was both large enough and recent enough that our models could be properly trained without including songs which were no longer popular. If we'd included songs before 1990, we could run the risk of including songs that had musical techniques which were no longer as popular. Our second section contains model implementation. We created a 70/30 train/test split of our data and trained models such as linear and logistic regression, LDA, random forest, classification tree, etc. From these models came the 3 section, focused specifically on evaluating how well our models performed and selecting the best one to use from there. It is with this model that we were able to identify which aspects of a song tended to make it more popular, allowing us to develop suggestions for those in the industry. 


## Data Sources: 
    - https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=data_o.csv (data.csv)
    - https://www.kaggle.com/unanimad/grammy-awards

    
 