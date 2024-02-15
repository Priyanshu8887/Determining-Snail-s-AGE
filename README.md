# Determining-Snail-s-AGE
This work contains a machine learning model using all the four types of Regression, which is used to find the age of marine snails called as Abalones. Customarily, the age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope. But it is a tedious and time-consuming task. Therefore, other measurements, which are easier to obtain, are used to predict age.<br>
______
Attributes: We have given eight attributes which includes
* Length : Longest shell measurement (in mm).
* Diameter : Diameter of the shell calculated as perpendicular to length (in mm).
* Height : Height of the shell with meat in shell (in mm).
* Whole weight : Weight of whole abalone (in grams).
* Shucked weight : Weight of meat (in grams).
* Viscera weight : Gut-weight after bleeding (in grams).
* Shell weight : Weight of the shell after being dried (in grams).
* Rings : Number of rings in a shell. (Adding 1.5 to the number of rings gives the age of abalone in years).<br>
Rings is the target attribute others are features used for predicting rings.<br>

Simple Linear Regression Model:
- The accuracy for this model is around 74.681% for training data and around 74.859%.
<img src = "" >

Multivariate Linear Regression Model:
- The accuracy for this model is around 77.802% for training data and around 77.393%.

Polynomial Regression Model:
- For different value of degree of polynomial there is different accuracy.
- To find the accurate value of p, I have used albow method which gives p = 5, so the maximum accuracy is for p = 5..
- The accuracy for trainind data is 75.301% and for testing data 75.488%
<img src = "" >

Multivariate Polynomial Regression Model:
- For this still p = 5 is the best degree of polynomial, so the maximum accuracy is for p = 5..
- The accuracy for this model is around 83.784% for training data and around 90.923%.
<img src = "" >
- From the figure we can see after p = 5 accuracy with p is is almost constant, so p = 5 is the best degree of polynomial.
