# REAL-TIME-SUDOKU-SOLVER

![Screenshot (89)](https://user-images.githubusercontent.com/60431758/113689933-7b4aa280-96e8-11eb-838a-4726d47abf68.png)

The edges are detected using canny edge detector.

![Screenshot (91)](https://user-images.githubusercontent.com/60431758/113690017-974e4400-96e8-11eb-94f9-eecd3a99fb93.png)

From the detected contours, the contour with area greater than a threshold is chosen.

![Screenshot (90)](https://user-images.githubusercontent.com/60431758/113690389-f613bd80-96e8-11eb-8bd7-90ed18f90c57.png)

A warped image of the detected grid is created.

![Screenshot (92)](https://user-images.githubusercontent.com/60431758/113690716-5276dd00-96e9-11eb-9ee2-d6c633766ee1.png)

The warped grid is then splitted into 81 equal boxes.

![Screenshot (94)](https://user-images.githubusercontent.com/60431758/113690748-5b67ae80-96e9-11eb-9564-4adfc53128d8.png)

Now some preprocessing is applied on each of the boxes which includes removing the borders,adaptive thresholding,and moving the number in the centre.

![Screenshot (95)](https://user-images.githubusercontent.com/60431758/113691113-bdc0af00-96e9-11eb-8b3e-eced002e4332.png)

Now the images are ready to be detected by our CNN model. The model is trained using 10000 images with 25 epochs.












