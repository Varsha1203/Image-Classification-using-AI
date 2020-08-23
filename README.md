# Face-Detection

The trained model stored its weights in a file name called 'model_weights.h5'

The saved model has been loaded in a python notebook called 'savedModel.ipynb'

Only file to be run is savedModel.ipynb while it asks for input image name for which you want to find the person face

Ensure two things before running :

  1. Path of the image to be tested : 
       The path of the input image should be initialized as string in savedModel.ipynb , else the input image should be in the same folder where the rest of the code has.

  2. The extension of the image :
        The extension of the input image here by default is 'jpeg'. You can change the extension in 'savedModel.ipynb'
        
After ensuring these two things, run the last cell of savedModel.ipynb. It prompts a tkinter window where the user will need to give only the image name to be tested..
