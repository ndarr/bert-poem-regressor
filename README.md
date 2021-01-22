# BERT poem regressor
BERT model trained for predicting scores for various categories given poetry. Both notebooks are best run in Google Collaboratory but can be also used locally with a Jupyter runtime.


## Setup
Download the score file named as *normalized_scores.csv* with a mapping from poems to scores and a line ending token *<br>*.
```shell
wget https://raw.githubusercontent.com/ndarr/pairwise-preference-learning/main/scores/normalized_scores.csv
```

## Run
Follow the code in *BertPoems.ipynb*. The BERT model to be used can be varied by asigning a different name to the variable bert_name in the second cell.

## Analysis
The produced losses and models can be used for further investigation by running the cells in *BERT_Poems_Analysis.ipynb*.
