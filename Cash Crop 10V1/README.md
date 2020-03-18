
This is the first true research for models to build our plant identifier.

If you want to run this yourself:
Download the following into your folder:
img_csv
img_dl.ipynb - Run this first - You only need to do this once
img_preprocess.ipynb - Run this second - You only need to do this once
InceptionResNetV2
ResNet50 
img_predict


img_csv is where the csv's containing all the image links are that the dl and preprocess programs need to retrieve and organize the set of training, validation, or testing images.

img_predict is the folder I store random images I want to test the model out with outside of the initial set of training, validation, or testing images.

InceptionResNetV2, ResNet50 and other folders contain the models and all the code I used to train the said model.

Note: In the code provided I did not automate all file pathing. Thus, you will need to specify the base directory in all the models, dl, and preprocessing programs such that the correct dependencies are in place to run the models.




