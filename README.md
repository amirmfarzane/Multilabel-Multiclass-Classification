## Description

Multilabel multiclass classification images on Fashion Product Images Dataset dataset by tensorlflow.
I train 7 seprate model to get result of each class and finaly train a multioutput model.

## Dataset
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset?resource=download
44k products with multiple category labels, descriptions and high-res images that i just use 25000 image with low quality for train.

## Result
f1-score on test set for multioutput and single output models.

Label| Multioutput| Singleoutput
-----------|-----------|-----------
Master category| 94| 97
Gender| 83| 84
Usage| 86| 86
Season| 64| 64
Base color| 87| 91
Master category| 80| 85
