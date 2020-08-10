# Face_recognition

Face Recognition using OpenCV in Python



### Prerequisites

Numpy</br>
OpenCV

#### Note: Please install opencv-contrib-python package instead of opencv-contrib as it contains the main modules and also contrib modules.

### Installing

Install Numpy via anaconda:
```
conda install numpy
``` 

Install OpenCV via anaconda:
```
conda install -c menpo opencv
```


## Data Collection

Run Data_collection_opencv.ipynb  to collect 100 training and 100 test data of subjects facees 

## Training a VGG-16 model

1.Place some test images in TestImages folder that you want to predict  
2.Place Images for training the classifier in Train folder.If you want to train clasifier to recognize multiple people then add each persons folder in separate label markes as 0,1,2,etc and then add their names along with labels in a dictonary.
3.Train the model for 5 epochs on your mTraining data set

## Testing the model using openCV
Run prediction video.ipynb to see the model working


## Acknowledgments
* https://www.superdatascience.com/opencv-face-recognition/
* https://pythonprogramming.net/haar-cascade-face-eye-detection-python-opencv-tutorial/
