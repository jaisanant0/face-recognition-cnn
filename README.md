# face-recognition-cnn
This repository will help you to build face-recognition with the help of convolutional neural network.

![gif](https://j.gifs.com/vlo1WX.gif)

## Getting strated 
The scripts are based on Keras implementation of OpenFace. All the required files are provided with it. Just clone the repository.

## Usage

1. Make a folder names **images** inside the cloned directory.
2. Place all the images of the person you want to identify in **images** folder.
3. Rename the image with person name.   
      Example : pajksbefs.jpg -> <name of person in the image>.jpg
4. Run 
```
python3 create_embeddings.py
```
  This will create the 128-D vector of the faces of person in the images folder.

5. Run
```
python3 face-recognition.py
```
  This will identify the person present in webcam's view.
      
Note :
Running **face-recognition.py** and **create_embeddings.py** might take some time due to loading weights on the network. Once the weights are loaded, it will run smoothly.



