# Agricultural Product Classification
Image classification using [mdwaquarazam](https://www.kaggle.com/datasets/mdwaquarazam/agricultural-crops-image-classification) datasets with pre-trained [EfficientNetV2L](https://www.tensorflow.org/api_docs/python/tf/keras/applications/resnet_v2/ResNet50V2) model. 

Transfer learning technique was used to build this model. Transfer learning is an optimization that allows rapid progress or improved performance when modeling the second task. Transfer learning is the improvement of learning in a new task through the transfer of knowledge from a related task that has already been learned. (source: [machinelearningmastery.com](https://machinelearningmastery.com/transfer-learning-for-deep-learning/#:~:text=Transfer%20learning%20is%20an%20optimization,that%20has%20already%20been%20learned.)) I try EfficientNetV2L because the model was able to predict [Flowers-102 dataset](https://www.tensorflow.org/datasets/catalog/oxford_flowers102) with 99.65% accuracy (source: [paperswithcode.com](https://paperswithcode.com/paper/sharpness-aware-minimization-for-efficiently-1)).

# Crops example :
![This is an image](https://i.ibb.co/3pqX94Z/Screen-Shot-2022-09-12-at-20-13-56.png)

# Model Architecture :
![This is an image](https://i.ibb.co/cTyTymj/download.png)

# Result :
![This is an image](https://i.ibb.co/wgC0v9w/download-1.png)

Accuracy : 98.547%
