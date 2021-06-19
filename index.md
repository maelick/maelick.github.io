## Portolio

This page highlights some of the work I produced while conducting research at the University of Oulu.

### pytextpipe

[pytextpipe](https://github.com/M3SOulu/pytextpipe) is a (WIP) Python library for producing a pipeline/workflow for evaluating combinations of various ML classification algorithms, NLP preprocessing steps and data sampling techniques on different datasets.
It is partly based on a paper presented at [MSR 2021](https://arxiv.org/pdf/2103.13165.pdf).

### FinnishSentiment

[FinnishSentiment](https://github.com/M3SOulu/FinnishSentiment) is a package for conducting sentiment analysis of Finnish text using logistic regressions.
The data used for training the model is based on almost 2000 tweets about COVID-19 that were manually classified and the paper behind it is currently under review.
There is also [second repository](https://github.com/M3SOulu/FinnishSentimentCOVID19) containing additional scripts for replicating all the results of the paper.

### 20-MAD

20-MAD is a dataset that was shared and [presented during MSR 2020](https://www.youtube.com/watch?v=9j6PnUyoyyg).
The data itself is [hosted at OSF](https://osf.io/kvxr4/).
The main code for data extraction and processing is hosted in a [GitHub repository as an R package](https://github.com/M3SOulu/MozillaApacheDataset-Rpackage) while a [second repository](https://github.com/M3SOulu/MozillaApacheDataset) is used for gluing together [different packages](https://github.com/M3SOulu/MozillaApacheDataset/tree/master/packages), documenting the data and contains a few additional scripts.
A [Docker image](https://hub.docker.com/repository/docker/claesmaelick/mozilla-apache-dataset) is also available for replication purposes.

### Natural Language or Not (NLoN)

[NLoN](https://github.com/M3SOulu/NLoN) is an R package to automaticelly detect whether a line of text is natural language or not.
This work is the result of a [paper presented at MSR 2018](https://mmantyla.github.io//2018_Mantyla_MSR_natural-language-nlon.pdf).

### RSentiStrength and RSenti4SD

[RSentiStrength](https://github.com/M3SOulu/RSentiStrength) and [RSenti4SD](https://github.com/M3SOulu/RSenti4SD) are two simple R packages for running two sentiment analysis tools: [SentiStrength](http://sentistrength.wlv.ac.uk/) and [Senti4SD](https://github.com/collab-uniba/Senti4SD)

### TextFeatures

[TextFeatures](https://github.com/M3SOulu/TextFeatures) is an R package for generating features to feed to machine learning for text classification.

### EmoticonFindeR

[EmoticonFindeR](https://github.com/M3SOulu/EmoticonFindeR) is a package for detecting emoticons and emojis from text data.
