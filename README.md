# mnist-dataset-example

In this code, I've followed the MNIST dataset example, predicting the actual number value (0-9) of a 28x28 pixel image. I've found the best KNeighborsClassifier parameters by GridSearchCv. Then I've added the rotated images by right, left, up and down and added to the actual dataset, used the KNeighborsClassifier with the best parameters to predict the new rotated images.

Feature plan: To increase accuracy from 0.88 to 0.97 (the original dataset accuracy)
