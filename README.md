# REAL-TIME-SUDOKU-SOLVER

![Screenshot (89)](https://user-images.githubusercontent.com/60431758/113689933-7b4aa280-96e8-11eb-838a-4726d47abf68.png)

## The edges are detected using canny edge detector.

![Screenshot (91)](https://user-images.githubusercontent.com/60431758/113690017-974e4400-96e8-11eb-94f9-eecd3a99fb93.png)

## From the detected contours, the contour with area greater than a threshold is chosen.

![Screenshot (90)](https://user-images.githubusercontent.com/60431758/113690389-f613bd80-96e8-11eb-8bd7-90ed18f90c57.png)

## A warped image of the detected grid is created.

![Screenshot (92)](https://user-images.githubusercontent.com/60431758/113690716-5276dd00-96e9-11eb-9ee2-d6c633766ee1.png)

## The warped grid is then splitted into 81 equal boxes.

![Screenshot (104)](https://user-images.githubusercontent.com/60431758/113702144-bfdd3a80-96f6-11eb-9381-4bbc8eb780c6.png)

## Now some preprocessing is applied on each of the boxes which includes removing the borders,adaptive thresholding,and moving the number in the centre.

![Screenshot (105)](https://user-images.githubusercontent.com/60431758/113702174-c5d31b80-96f6-11eb-9aef-1e336bdb8614.png)

## Now the images are ready to be detected by our CNN model. The model is trained using 10000 images with 25 epochs.

![Screenshot (96)](https://user-images.githubusercontent.com/60431758/113702391-1185c500-96f7-11eb-96f4-eed8c465317e.png)

## Images of all the numbers were present in almost equal number.

![Screenshot (98)](https://user-images.githubusercontent.com/60431758/113702559-4d208f00-96f7-11eb-8f6e-6802556e6875.png)










