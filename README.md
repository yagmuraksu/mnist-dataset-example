# mnist-dataset-example

In this code, I've followed the MNIST dataset book* example, predicting the actual number value (0-9) of a 28x28 pixel image. I've found the best KNeighborsClassifier parameters by GridSearchCv. Then I've added the rotated images by right, left, up and down and added to the actual dataset, used the KNeighborsClassifier with the best parameters to predict the new rotated images.

* https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/
