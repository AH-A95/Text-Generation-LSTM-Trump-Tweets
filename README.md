# Text-Generation-LSTM-Trump-Tweets

This is a LSTM model that generations Trump tweets. Although the file contained tweets almost all of his tweets, I only used tweets from 2016 election day to that same date in 2017, for time/memory purposes. Anything more would've have taken alot longer to train the model. I didn't want to use anything before he started running for president either, because those tweets are irrelevant to his position now. 

Because of the low epochs of the model + small sample of tweets, the model reverts to predicting the same characters/words after a couple of characters. That could also be the year of tweets I chose. The president was embroiled in alot of scandals right after his election,and chose to hammer home alot of similar talking points in his tweets, which made it harder to train
with a small amount of epochs. With more epochs/a larger sample of tweets, this tweet predictor should preform significantly better, but this works okay considering time/memory contraints. It predicts characters that form actualenglish words. Maybe if we introduced a function that generated more creative/diverse text generation, that could help as well. 
