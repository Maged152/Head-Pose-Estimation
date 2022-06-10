# Head pose estimation

## first we use the data of faces & angles (yaw,pitch,roll) AFLW2000 ,and we use mediapipe to extract 468 point of each face then combine the two into one data frame which  consists of the points and the angles

## second we train three models (randomforest) to estimate the angles , used random search grid to help finding best model

## finally we draw the axis to see the results on images,video or webcam

### Here are some results

![](./outputimg2.jpg)  ![](./outputimg3.jpg) 

![](./outputimg1.jpg)



https://user-images.githubusercontent.com/100991836/173145546-87e41cea-e639-4102-af05-1e933ab3e3b0.mp4

