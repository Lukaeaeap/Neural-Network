# Neural-Network

I started this project to learn about neural networks

Because some of the libraries are named different because of newer python versions you can install the right library with the following commands:
pip install python-mnist
pip install numpy
pip install opencv-python
pip install pickle-mixin
pip install copy

If any of the libraries do not work try one of the following commands to remove another version of the library that doesnt work:
pip uninstall mnist
pip uninstall cv2
pip uninstall pickle

To use the neural network for the first time, scroll done in the code and make sure training is on (by giving the boolean as value True). Than if the model has been trained you can turn this boolean to False.
In the Test-plaatjes folder are a few examples I drew and which name you can insert in the image_f string. 

To play around and test if the program works, open the 'tekening.png' file in paint. And when you draw a digit you can press ctrl + s to save it and than you can run the code which will immiediatly convert the image and it will be forwarded trough the NN to classify it as a certain digit. Read the console for the output.
