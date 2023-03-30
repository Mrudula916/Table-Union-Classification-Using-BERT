

## Final Project: Table Union Classification using Language Models. - Mrudula Krishna Prasad (CS7290: Spl Topics in Data Science)

This repository consists of all the files pertaining to this project. The following will explain how to run the code.

## Libraries required to run this code

The requirements.txt file can be installed to get all the libraries required to run the code.

## Generate embeddings

The Data_Pre_processing_using_BERT.ipynb file generates table embeddings. The pre-trained embeddings are present in the embeddings.pt and zero_embeddings.pt. 

embeddings.pt - stores the table embeddings of all the tables that can be unioned according to the groundtruth table. (positive samples)
zero_embeddings.pt - stores the table embeddings of all the tables that cannot be unioned according to the groundtruth table. (negative samples)

## Classification task

Both the embedding files are necessary to run the classification task. 

## Any IDE that can run jupyter notebooks can be used to run this code.

## To Download the pre-trained embeddings and other data items, please follow this link: https://drive.google.com/drive/folders/17aahX12l7pNkcHNH1XuTdoXASTKMItHV?usp=sharing

## NOTE: All the paths in the code are given as drive links. If files are being used from local directories (or any other paths), the format of the file paths need to changed accordingly. Also, the dataset is the private property of Data Lab, Northeastern University. For access, permission is required.

## For any further queries/clarifications, please contact:
Mrudula Krishna Prasad - krishnaprasad.m@northeastern.edu
