# CodeFlash

The project is to recognize pencil sketch images which can be helpful in investigations and forensics.
The application is run using Flask. The images are trained using a object recognition database, and sketch images of the objects are uploaded.
Since this can be used as transfer learning, changing the dataset images will be sufficient for different applications.

# Dataset
Caltech101: http://www.vision.caltech.edu/Image_Datasets/Caltech101/

# File Information
maincode.html: Contains the html code for uploading a image. This is connected to the backend in flask.py file.

flask.py: Contains the flask application. Set of functions are defined which uses the h5 file of the trained model for the prediction of the image.

sketchrecognition.py: Containts the main deep learning model. Keras is used as a High Level API using tensorflow backend.

The model is still being trained due to computational difficulties.
