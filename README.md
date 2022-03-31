# Aluminium Al-A356 Classification

This project is aimed to classify the Aluminium Al-A356 into 5 classes from the microstructure image. Al-A356 can be classified by Eutectic Silicon shape. The lower class is larger and longer than the higher class. The main problem in Aluminium Al-A356 classification is the similarity of the adjacent classes which is very hard to classify by the human perceptual, so I use the CNNs(Convolutional Neural Networks) to solve this problem.

Prediction result:


     precision    recall  f1-score   support
     level 1     0.9765    0.9541    0.9652       305
     level 2     0.8329    0.9682    0.8954       314
     level 3     0.9754    0.9358    0.9552       296
     level 4     0.9844    0.9200    0.9511       275
     level 5     0.9253    0.8814    0.9028       295
     accuracy                        0.9327      1485
     macro avg   0.9389    0.9319    0.9339      1485
     weighted avg  0.9372    0.9327    0.9334      1485

![output_best](https://user-images.githubusercontent.com/47117440/161067908-5c851943-26e8-452b-a6e5-ee28f3e1d11d.png)

ROC curve:

![roc_curve_best](https://user-images.githubusercontent.com/47117440/161069230-4e71ad79-6d53-4f1e-acd3-c708a13e9f16.png)

For the full code and result, you can see it on the attached Jupyter notebook file.
