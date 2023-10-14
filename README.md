# HutCRS

The implementation of _HutCRS: Hierarchical User-Interest Tracking for Conversational Recommender System_ (EMNLP 2023). 

The code is partially referred to [MCMIPL](https://github.com/ZYM6-6/MCMIPL).

## Environment Settings
python: 3.9.15

pytorch: 1.12.1 

dgl: 1.0.1

## Data Preparation
We have released the data, including lastfm_start, yelp_star,Amazon-Book and MovieLens, which is processed in [MCMIPL](https://github.com/ZYM6-6/MCMIPL)).


## Training
`python RL_model.py --data_name <data_name>  --entropy_method entropy --ask_large_fea_num 4 --choice_num 2 --classify`

## Evaluation
`python evaluate.py --data_name <data_name> --load_rl_epoch <checkpoint_epoch> --entropy_method entropy --ask_large_fea_num 4 --choice_num 2 --classify`

