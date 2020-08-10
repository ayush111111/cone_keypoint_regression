# Cone keypoint Regression

Objective:
  You have to extract 7 essential key-points on cones laid out in the  simulator (or your own track). This can be done by extracting an image and using (and training) a deep learning model (eg. a Resnet) which can be of your choice.



1. Resources Used
  https://arxiv.org/pdf/1902.02394.pdf#figure.4
  https://github.com/cv-core/MIT-Driverless-CV-TrainingInfra
  #cvc-yolov3-dataset-with-formula-student-standard-is-open-sourced-here (RektNet).


2. Model Architecture :


3. Loss Function used :
  Cross ratio Loss

![](https://drive.google.com/file/d/1D49YpyfIiYAoHzOG6OAN3IBfLW3M8ODN/view?usp=sharing)


  The  cross-ratio  (Cr)  is  a  scalar  quantity  and  can  be calculated with 4 collinear points or, 5 or more non-collinearpoints. It is invariant under a projection and the process of acquiring images with a camera is essentially a projective transform. The  cross-ratio  is  preserved,  both  on  the  2D projection  of  the  scene  (the  image)  and  in  3D  space  where the object lies.
