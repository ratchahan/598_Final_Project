# 598_Final_Project
Final Project for CS 598 Deep Learning for Healthcare

>📋  A template README.md for code accompanying a Machine Learning paper

# SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS

This repository is the official implementation of [SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS](https://arxiv.org/abs/1609.02907). 

>📋  Our code submission is in the form of a jupyter notebook. This was approved in Campuswire post #1957

## Requirements

All additional requirements are installed in the notebook:

```setup
!pip install dgl
```


## Training and Evaluation

To train and evaluate the model(s) in the paper with the three citation network datasets, run one of these three commands (note this is included in a cell in the notebook):

```train
citeseer_dataset =  dgl.data.CiteseerGraphDataset()
train_and_test_model(citeseer_dataset)
```

```train
cora_dataset =  dgl.data.CoraGraphDataset()
train_and_test_model(cora_dataset)
```

```train
pubmed_dataset =  dgl.data.PubmedGraphDataset()
train_and_test_model(pubmed_dataset)
```


## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 

