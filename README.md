# wrinkle-detection
Wrinkle Detection over the upper part of the footwear in leather.


# Global Descriptors

Hu Moments, Haralick Features, Intensity Histogram

# Classification Methods

SVM Linear and KNN classifiers

# Process

A data set for training and testing is required. The first cell of the code runs the training path and extract every descriptor for the 3 global methods and then concatenate them into a single feature vector.

The testing and machine learning methods of KNN and SVM Linear are used with a previous standarization of the data. The testing data is read, features are extracted the same way and data is transoformed to validate the results by calculating accuracy, precision, specificity, sensitivity and error.

# Environment:

- Anaconda
- Spyder
- Python 3.7

# Libraries

- OpenCV
- Scikit-Image
- Scikit-Learn
- Haralick Features

# Note 

The data set and any further information can be required at sasb1989@gmail.com
