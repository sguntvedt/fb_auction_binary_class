# facebook_bot_detection
### Contents
This repository contains three Jupyter notebooks that outline my approach for the   
"Facebook Recruiting IV: Human or Robot?" contest hosted on Kaggle. Enclosed in the first notebook are methods that examine the log data provided and produce the first round of features. The second notebook produces more features and begins model testing and evaluation of models. Lastly, the third notebook takes the best model, performs hyperparameter optimization, and generates predictions.

### Description of CSV Files
1. Download competition data from the following link and place csv files into datasets repository: https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data
2. Run the 1_auction_eda.ipynb notebook to create first set of features csv "bids_w_scores_mean.csv", which is also placed in the datasets repository upon running.
3. Run the 2_auction_feature_gen.ipynb notebook to create the second set of features csv "w_inactive_auc_bid_behavior_df.csv", which will be placed in the datasets repository upon running.
4. Run the 3_xgboost_tune.ipynb to generate the predictions csv "submissions1.csv", which will be placed in the submissions repository upon running.

### Libraries
1. For Data Cleanup and Feature Generation: numpy, pandas, sklearn, scipy
2. For Predictive Modeling: sklearn, xgboost
3. For Visualizations: matplotlib, seaborn

### Run Time/Hardware
Runs in about 35 minutes on a fairly high-powered desktop (i7-4790) with 16 gb of RAM. May clog up the ram on smaller machines.
