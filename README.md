# dog_breed_identification
end-to-end multi-class image classifier (dog breed identification) using tensorflow and tensorflow hub.
## 1. Problem:
Identifying the breed of a dog though an image.

## 2. Data:
Using data from dog breed identification competition on kaggle. source: https://www.kaggle.com/c/dog-breed-identification/data

## 3. Evaluation:
evaluated on Multi Class Log Loss between the predicted probability and the observed target.
Source: https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## 4. Features:
We are dealing with image data (unstructured data), it's best to use deep learning/transfer learning.
* There are 120 breeds of dog (this means there are 120 different classes).
* There are 10,222 train sample images.
* There are 10,357 test images. 
* test set images have no label.

## Submission Score:
Submissions are evaluated on Multi Class Log Loss between the predicted probability and the observed target.
![](https://github.com/luigivendetta/dog_breed_identification/blob/master/subscore.png)
