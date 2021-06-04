first you need to install the packages from requirements.txt

 how to install:
open cmd in current diractory and type this command: pip install -r requirements.txt

Now to run the project: open FaceRecognition.ipynb and run all the cells

to re train the model for better accuracy add more data to the Dataset>Train>"add data to each class"

the output of the model is coded like the alphabet followed by the floder name of the class that is detected.



i converted the .pgm images to jpeg using Pixillion Image Converter (crack) as they are unsupported by tensorflow.

Project Flow:
Fist i downloaded the two face dataset from the given url
then i converted each image from pgm to jpg using a software Pixillion.
then i manually merge the two dataset for each class 0-25 you can find the merged data in Dataset>>Train.
then i open training.ipynb and load the pretrained model and retrain it on our dataset.
after training you can check the accuracy of the model is around 99%
after it, i open FaceRecognition.ipynb and deploy the model to recognize the faces from the video stream.
