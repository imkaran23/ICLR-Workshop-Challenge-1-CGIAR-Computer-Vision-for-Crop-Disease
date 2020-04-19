# ICLR-Workshop-Challenge-1-CGIAR-Computer-Vision-for-Crop-Disease
A machine learning algorithm to correctly classify if a plant is healthy, has stem rust, or has leaf rust.

The evaluation metric for this challenge is Log Loss.

Some images may contain both stem and leaf rust, there is always one type of rust that is more dominant than the other, i.e. you will not find images where both appear equally. The goal is to classify the image according to the type of wheat rust that appears most prominently in the image.

The values can be between 0 and 1, inclusive.

ID          leaf_rust   stem_rust   healthy_wheat   
GVRCWM         0.63       0.98          0.21      
8NRRD6         0.76       0.11          0.56

Wheat rust is a devastating plant disease that affects many African crops, reducing yields and affecting the livelihoods of farmers and decreasing food security across the continent. The disease is difficult to monitor at a large scale, making it difficult to control and eradicate.
