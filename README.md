
# PRDECT-ID: Indonesian product reviews dataset for emotions classification tasks

This repository contains datasets related to our paper [PRDECT-ID: Indonesian product reviews dataset for emotions classification tasks](https://doi.org/10.1016/j.dib.2022.108554). This dataset is also available on the [Mendeley Data website](https://data.mendeley.com/datasets/574v66hf2v/1).

## Value of the Data

 - To the best of our knowledge, the [PRDECT-ID dataset](https://github.com/rhiosutoyo/PRDECT-ID-Indonesian-Product-Reviews-Dataset/blob/main/Dataset/PRDECT-ID%20Dataset.csv) is the first Indonesian product reviews dataset annotated with emotions.
 - The PRDECT-ID dataset contains 5400 product reviews, spread over 29 different product categories and ready to use for an emotions classification task.
 - The annotation process follows emotions annotation criteria created by an expert in clinical psychology.
 - The PRDECT-ID dataset offers additional attributes from the product reviews for other text classification tasks. For instance, sentiment classification by using the “Sentiment” data.

## Data Annotation

 - Each product review is annotated with a single emotion with [Shaver’s emotions model](https://onlinelibrary.wiley.com/doi/abs/10.1111/1467-839X.00086).
 - The annotator label each product review based on the content of the review from the customers.
 - The annotation process follows the emotions annotation criteria created by lecturers and experts in clinical psychology.

## List of Attribute
Although this work focuses on product reviews, other details related to the product review are captured, such as Price, Number Sold, and Total Review. The list of attribute is shown in Table below.

|Attribute| Description |
|--|--|
| Category | Product classification by category |
|Product Name|Name of the reviewed product|
|Location|City name of the shop or product seller|
|Price|Price in IDR of the reviewed product |
|Overall Rating|Overall product rating|
|Number Sold|Total number of products sold|
|Total Reviews|Total number of reviews given by the customers|
|Customer Rating|Product rating (range 1 to 5) from the customers|
|Customer Review|Product reviews given to the product by the customers|
|Sentiment|Sentiment labels (i.e., Positive, Negative)|
|Emotion|Emotion labels (i.e., Anger, Fear, Happy, Love, Sadness)|

##  Citation
If you use this dataset in a scientific publication, we would appreciate using the following citations:

### Plain Text
Sutoyo, R., Achmad, S., Chowanda, A., Andangsari, E. W., & Isa, S. M. (2022). PRDECT-ID: Indonesian product reviews dataset for emotions classification tasks. _Data in Brief_, _44_, 108554.

### BibTeX
```
@article{SUTOYO2022108554,
title = {PRDECT-ID: Indonesian product reviews dataset for emotions classification tasks},
journal = {Data in Brief},
volume = {44},
pages = {108554},
year = {2022},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2022.108554},
url = {https://www.sciencedirect.com/science/article/pii/S2352340922007612},
author = {Rhio Sutoyo and Said Achmad and Andry Chowanda and Esther Widhi Andangsari and Sani M. Isa},
keywords = {Natural language processing, Text processing, Text mining, Emotions classification, Sentiment analysis},
abstract = {Recognizing emotions is vital in communication. Emotions convey additional meanings to the communication process. Nowadays, people can communicate their emotions on many platforms; one is the product review. Product reviews in the online platform are an important element that affects customers’ buying decisions. Hence, it is essential to recognize emotions from the product reviews. Emotions recognition from the product reviews can be done automatically using a machine or deep learning algorithm. Dataset can be considered as the fuel to model the recognizer. However, only a limited dataset exists in recognizing emotions from the product reviews, particularly in a local language. This research contributes to the dataset collection of 5400 product reviews in Indonesian. It was carefully curated from various (29) product categories, annotated with five emotions, and verified by an expert in clinical psychology. The dataset supports an innovative process to build automatic emotion classification on product reviews.}
}
```
