# wrinkle-detection
Wrinkle Detection over the upper part of the footwear in leather. This approach was coded in order to solve an issue of wrinkles over the upper part of footwear in leather, which means it might not be suitable for other porpuses. However, feel free to test it out in other scenarios.


# Global Descriptors

Hu Moments, Haralick Features, Intensity Histogram

# Classification Methods

SVM Linear and KNN classifiers

# Process

A data set of images for training and testing is required. The first cell of the code runs the training path and extract every descriptor for the 3 global methods and then concatenate them into a single feature vector.

The testing and machine learning methods of KNN and SVM Linear are used with a previous standarization of the data. The testing data is read, features are extracted the same way and data is transoformed to validate the results by calculating accuracy, precision, specificity, sensitivity and error.

# Environment:

- Anaconda Environment
- Spyder
- Python 3.7

# Important Libraries

- OpenCV
- Scikit-Image
- Scikit-Learn
- Haralick from Mahotas
- Glob

# Note 

The data set for training and testing or any further information can be requested at sasb1989@gmail.com
