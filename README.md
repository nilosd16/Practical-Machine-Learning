Practical Machine Learning - Prediction Assignment Writeup
========================================================

This document describe the analysis done for the prediction assignment of the practical machine learning course.

The first part is the declaration of the package which will be used. In addition to caret & randomForest already seen on the course, I used Hmisc to help me on the data analysis phases & foreach & doParallel to decrease the random forrest processing time by parallelising the operation.
Note : to be reproductible, I also set the seed value.


