# 142FinalProject

Data Sources: 
    - https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=data_o.csv (data.csv)
    - https://www.kaggle.com/unanimad/grammy-awards


Project Outline:

1. Data Cleaning/Processing Options:
    - Conduct NLP on song titles
        - NLP processing, then dummy encode 
    - Include more data
        - Most popular genre of each year
        - **Grammy binary value**
        - Cost of producing the song
    - Pick specific years (1990-2019)
    - Possibly dummy encode other columns
    
2. Build our Models:
    - Train/Test Split
        - Randomly
        - 70/30
    - Linear Regression (OSR2 + MAE)
    - Regression Tree (OSR2 + MAE)
    - Add threshold for popularity 
        - We can manually figure this out
    - Add binary column
    - Implement threshold on those two models^
    - Logistic Regression
    - Classification Tree
    - Vanilla Bagging
    - Random Forest
    - Boosting
    - LDA 
    - Compare models + decide which one to use
    
3. Business Analysis
    - Key factors to increase popularity of song
        - Feature analysis
    - Assess loss + cost of producing a song
    
 