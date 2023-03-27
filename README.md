# Banknote Classification


Summary:
In this project, I used a dataset that has 4 features that describe a banknote, and one column that classifies the banknote as authentic or not. After exploring, and then transforming the data to adjust for skewness, I try 3 different models to predict the authenticity of the banknote.

Attribute Information
1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)

Data was downloaded from:
https://www.kaggle.com/code/nataliakhol/banknote-classification-with-svm-from-scratch/data
https://archive.ics.uci.edu/ml/machine-learning-databases/00267/

Data Set Information
Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

Source
Owner of database: Volker Lohweg (University of Applied Sciences, Ostwestfalen-Lippe, volker.lohweg '@' hs-owl.de)
Donor of database: Helene DÃ¶rksen (University of Applied Sciences, Ostwestfalen-Lippe, helene.doerksen '@' hs-owl.de)
