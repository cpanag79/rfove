# RFOVE - Region-based Fitting of Overlapping Ellipses - Cells Segmentation


This code is a simple  implementation of METHOD RFOVE PROPOSED IN [1] 

You can find more details in [1]  
Matlab Code: https://www.mathworks.com/matlabcentral/fileexchange/74200-rfove

Files: runRFOVE.m : implemetation of the method
  
[1] C. Panagiotakis and A.A. Argyros, "Region-based Fitting of Overlapping Ellipses and its 
Application to Cells Segmentation", Image and Vision Computing, Elsevier, vol. 93, pp. 103810, 2020.

You can download Datasets/Code/Results 
from: https://sites.google.com/site/costaspanagiotakis/research/cs 

RFOVE is completely unsupervised, operates without any assumption or prior knowledge on the object’s shape and extends and improves the Decremental Ellipse Fitting Algorithm (DEFA) [1]. Both RFOVE and DEFA solve the multi-ellipse fitting problem by performing model selection that is guided by the minimization of the Akaike Information Criterion on a suitably defined shape complexity measure. However, in contrast to DEFA, RFOVE minimizes an objective function
that allows for ellipses with higher degree of overlap and, thus, achieves better ellipse-based shape approximation.
