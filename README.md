# Human-Protein-Atlas-Image-Classification
Team name: Play To Win  
Members: Shilong Yin, mapusaurus  


Models for Kaggle competition: Human Protein Atlas Image Classification:  
https://www.kaggle.com/c/human-protein-atlas-image-classification/leaderboard.


InceptionResNetV2: CNN with pretrained model  
credits:  https://www.kaggle.com/byrachonok/pretrained-inceptionresnetv2-base-classifier.  
GapNet: CNN with GAP layer  
credis: https://www.kaggle.com/rejpalcz/gapnet-pl-lb-0-385.  
# Abstract
## Motivation
Providing the confocal microscopy image, we are able to see deep inside human cells and their organelles. In order to better understand the function of cell, the best way is to determine the distribution pattern of protein. Therefore, it is a hot topic in the research field to develop models that are able to classify the mixed patterns of proteins in cells, which is the main task of our project.
## Results
Based on kernels from Kaggle, we are able to construct a protein atlas image classifier with data generator, train-ing and validation splitter, neural network and threshold generator. Our model gives a prediction with the best score of 0.422.
