### Problem Statement

Should FIFA officials stand to benefit from making one subreddit for all soccer events?

### Background

Note: The word football is used over soccer typically around the world but in the US the word soccer is used to describe it. So for all intents and purposes, the word soccer will be used to avoid confusion. 


FIFA(Fédération Internationale De Football Association) has been around since 1904. They are a big soccer organization that has made the most money from any of the other previous World Cups this past year at Qatar in the 2022 World Cup. FIFA are trying to maximize profits now and thought they should research how social media: twitter,facebook and in this particular case reddit can icrease profit. They believe that people should be focused on the world cup when it comes around every 4 years but at the same time want people to still be able to transition back into league soccer when the world cup ends. A classification model that can determine the difference in the soccer and world cup subreddits would be beneficial for this issue.

### Data 

soccer.csv: The soccer subreddit dataset

world_cup.csv: The world cup subreddit dataset

world_cup_no_spam.csv: The world cup subreddit with almost 50 rows of nft 800 spam filtered out 

### Analysis

Though none of the models had accuracy scores above 90%, overall, the models performed well. Three of the four models had accuracy scores above 80 and the random forest model scored the highest at 86.9%. The most disappointing model was the KNN model that only had a 62% accuracy score and poor misclassification rate. Out of all the models the best one would be the random forest model. Though it is overfit, it scored best out of all the models on identify true positives and tied for the highest in identifying true negatives. The random forest model also had the lowere false negatives and false positives out of all the other models.

### Conclusions

Since the majority of models scored above 80% on accuracy FIFA can still stand to make good profits from having them seperate. If it was much harder to make a model to score at least 80% than the commonalities would have been enough to warrant combining them into one. For the next steps, on top of funding moderators for the world cup subreddit there could possibly be another subreddit made specifically for FIFA world cup 2026. This way moderating help would be easier to fund and the overall data on posts would be new enough to manage and leverage relevant advertisements. 
