# 2yp_final_repo
Final code repo for group 13
This is the Github Repo to be handed in along with our final notebooks and saved models.

The experiment is divied into 3 notebooks:

1 - data_cleaning.ipynb

This is the notebook where every collected domain is read and filtered. Unnecessary columns are removed, labels are encoded and nan-values are removed. The test- and validation domains are sampled with a set seed. Note: We could not fit all of the original datasets in the Repo, as we met a limit of 100MB on files through github. We therefore link the datasets in the bottom of the readme, so they can be downloaded off kaggle.com

2 - nlp_preprocessing_pipeline.ipynb

This is the notebook where Baseline models are made, Jensen Shannon divergence between domains is calculated and the domains for our proposed datasets are constructed.

3 - LSTM_model.ipynb

This is the notebook where our LSTM model is constructed and trained. We trained the model using Google Colaboratory and using Tensor-Processors to accelerate our code.

Due to filesize constraints on uploads to our Github Repository, we will provide links to the websites, where our datasets can be downloaded. The datasets found in "data/raw" are the versions which our datacleaning was performed on.

Hotel reviews - https://www.kaggle.com/datasets/datafiniti/hotel-reviews

Steam reviews - https://www.kaggle.com/datasets/andrewmvd/steam-reviews]

Disneyland reviews - https://www.kaggle.com/datasets/arushchillar/disneyland-reviews

Kindle store reviews - https://www.kaggle.com/datasets/meetnagadia/amazon-kindle-book-review-for-sentiment-analysis?select=all_kindle_review+.csv

imdb reviews - https://www.kaggle.com/datasets/columbine/imdb-dataset-sentiment-analysis-in-csv-format

amazon reviews - https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews?select=train.csv
