## Multilabel multiclass classification

I did multilabel multiclass classification images task on Fashion Product Images Dataset dataset by tensorlflow.
I train 7 seprate model to get result of each class(seven single output models) and finaly train a multioutput model.
I used oversampling and merged some classes of each label to increase accuracy.

## Dataset
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset?resource=download
44k products with multiple category labels, descriptions and high-res images that i just use 25000 image with low quality for train.

## Data Description

Context
Thr growing e-commerce industry presents us with a large dataset waiting to be scraped and researched upon. In addition to professionally shot high resolution product images, we also have multiple label attributes describing the product which was manually entered while cataloging. To add to this, we also have descriptive text that comments on the product characteristics.

Content
Each product is identified by an ID like 42431. You will find a map to all the products in styles.csv. From here, you can fetch the image for this product from images/42431.jpg and the complete metadata from styles/42431.json.

To get started easily, we also have exposed some of the key product categories and it's display name in styles.csv.

If this dataset is too large, you can start with a smaller (280MB) version here:
https://www.kaggle.com/paramaggarwal/fashion-product-images-small

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
