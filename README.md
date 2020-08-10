### Cone keypoint Regression

# Objective:
  You have to extract 7 essential key-points on cones laid out in the  simulator (or your own track)
![](https://github.com/ayush111111/cone_keypoint_regression/blob/master/Screenshot%20from%202020-08-10%2015-00-06.png)


# 1.Important links:

  https://arxiv.org/pdf/1902.02394.pdf#figure.4
  
  https://github.com/cv-core/MIT-Driverless-CV-TrainingInfra
  
  #cvc-yolov3-dataset-with-formula-student-standard-is-open-sourced-here (RektNet).


# 2.Model Architecture:
  Resnet blocks followed by a fully connected layer (of 14 neurons) is used .

# 3.Loss Function:
 

![CrossRatioLoss](https://github.com/ayush111111/cone_keypoint_regression/blob/master/Screenshot%20from%202020-08-10%2014-43-57.png)


  The  cross-ratio  (Cr)  is  a  scalar  quantity  and  can  be calculated with 4 collinear points or, 5 or more non-collinearpoints. It is invariant under a projection and the process of acquiring images with a camera is essentially a projective transform. The  cross-ratio  is  preserved,  both  on  the  2D projection  of  the  scene  (the  image)  and  in  3D  space  where the object lies.
