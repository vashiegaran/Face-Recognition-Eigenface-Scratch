# Face-Recognition-Eigenface-Scratch
Face Recognition and Detection using Eigenface method from scratch

1. Introduction
The objective of this project is to highlight the implementation of linear algebra in the field of computer vision and face recognition. Eigenface is the given name to  a set of eigenvectors. Eigenvectors is a set of features which characterize the global variation among face images.The basis of the eigenfaces method is the Principal Component Analysis (PCA).PCA is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.


2. Algorithm

  * Obtain face image and represent every image in a n^2 x m matrix
    Image

  * Compute the average face vector

  * Subtract each image with the mean vector face

  * Compute the eigen vectors

  * Select q eigenvectors to represent the new image space and project the new image into our new image space

  * The new image will be represented using the q eigenvectors

  * Face Detection
    -Subtract the new image which represented using q eigenvectors with mean vector face
    -If the difference is lower than a chosen threshold, the new image face is detected.
 
  * Face Recognition
    -Each image is represented using the eigenvectors
    -Each image is then subtracted with the new image which is represented with out eigenvectors
    -If the difference is lower than a chosen threshold, the new image face is classified to a class.

Please read the pdf notes for more detailed explanation with the help of mathematics


3. Application
 
  * Display data set of two classes
  ![Dataset](Image/1.png)

  * Mean image
  * 
![mean image](Image/2.png)

  * Each image with zero mean 
  * 
![zero mean image](Image/3.png)

  * Each image represented with q eigenvectors
  ![image eigenvectors](Image/4.png)

  * Mean Subtracted Test Image
  * 
![Test Image](Image/5.png)

  * Test image reprented using q eigenvectors
  * 
![Test Image eigenvectors](Image/6.png)

  
