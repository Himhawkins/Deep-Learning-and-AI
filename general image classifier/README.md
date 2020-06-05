This is a general image classifier to classify any data set of images into labelled classes using a configuralble neural network architecture.
Since the images are greyscaled,it is ideal for text images although slight modification to the flatten reshaping can increase usability to coloured images as well.

we use cv2 and pandas for data fetching.
and tensorflow for analysis.

this is a basic neural network without convolutions

this can fetch training data accuracy of upto 100 percent and test data accuracy upto 93 percent.

we use an adamoptimiser with softmax cost function and mini batch gradient descend.
