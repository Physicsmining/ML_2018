# Machine Learning Project 2 :Machine Learning for Science

`Teammates`: Yan Fu, Shengzhao Xia, Runzhe Liu

For this project we joined the lab in Chair of Economics and Management of Innovation. 

In this project, we did:

1. Data collection: web scrap from Web of Science and get over 350,000 paper records;
2. Name disambiguation: Disambiguation of different authors using same name;
3. Classification: Using models (eg. logistic regression, neural network), and converting keywords as vectors using word2vec to predict if one researcher is dismissed or not.

To reproduce our result one will need to:

1. Install libraries like `gensim`,`sklearn` on their computers;
2. Download [GoogleNews-vectors-negative300.bin.gz](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit) to do word2vec conversion, we did not include it in our submission because of its large size.

Below we will introduce files and functions in our repotory.
And because we cannot upload the whole dataset(the list is sensitive to some extent; and the whole dataset is very large) we comment out the code where origin data is used and save and load the output of preprocessing part. We do not delete the comments because we want to use them to show what we do in pre-processing).

## Auxiliary modules

* ### The folder `DataCollection`
This folder saves the codes used for webscraping and basic data cleaning, and it is *NOT* reproducible because we delete the username and password needed for apply request from WOS. 

* ### `datapreprocessing`

## Working notebook
* ### `Disambiguation.ipynb`: 
The name disambiguation part. We use kNN+LOF outlier dectection in it.

* ### `classification.ipynb`

zzzzzzz
