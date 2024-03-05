# **Handwritten Digits Classification**
--------------------------------------

## **Dataset Description**

The MNIST dataset is a widely used benchmark dataset in the field of machine learning and computer vision. It stands for "Modified National Institute of Standards and Technology" and is a collection of 28x28 pixel grayscale images of handwritten digits (0 through 9). It have Training set of 60,000 images and Testing set of 10,000 images.

We have performed Convolution Neural Network (CNN), K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) to classify the handwritten digits.

--------
## **Model Comparision Report**

```
+--------------+--------------------+-----------------+
| Model Name   | Testing Accuracy   | Ranking order   |
+==============+====================+=================+
| CNN          | 99.03%             | 1st(BEST)       |
+--------------+--------------------+-----------------+
| KNN          | 97%                | 2nd             |
+--------------+--------------------+-----------------+
| SVM          | 94%                | 3rd             |
+--------------+--------------------+-----------------+

```


**For CNN**

From the below graph we analyse that validation loss is minimum at 4 epochs, and accuracy is optimum at 4 epochs
So, we decided to train our model again till 4 epochs only with batch size of 30.

![image](https://github.com/anjanikmr39/Handwritten-Digits-Classification/assets/67219753/d2bc0ec3-6fe9-4847-ab32-59f697d91ccd)

![image](https://github.com/anjanikmr39/Handwritten-Digits-Classification/assets/67219753/e1e51e94-3b85-4268-9348-fc34343e1752)

--------
## **Challenges faced**:

No such challenges we have to faced because it is MNIST dataset, So No EDA we need to perform.

-----------
## **More information**
Visit this python file for more detailed analysis [HandwrittenDigits.ipynb](https://github.com/anjanikmr39/Handwritten-Digits-Classification/blob/master/HandwrittenDigits.ipynb).
