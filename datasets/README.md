Download the files `train.csv`, `test.csv`, `bids.csv`  and `sampleSubmission.csv` from https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data and place them in this directory.

Running the `1_auction_eda.ipynb notebook` will generate `bids_w_scores_mean.csv`, needed in the `2_auction_feature_gen.ipynb` notebook to continue feature generation.
Running the `2_auction_feature_gen.ipynb` notebook will generate `w_inactive_auc_bid_behavior_df.csv`, needed in the `3_xgboost_tune.ipynb` to create predictions.
