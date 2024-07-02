Python-Based Lung Cancer Detection ## Cancer Imaging Archive (TCIA) Dataset http://www.cancerimagingarchive.net/
Code files 
Programming has been done in a modular way.

PredictCancer.py: The last picture testing program
NeuralNetwork.py: MLP learning features with SKlearn and pickling the Weights
LungCancerTrain.py: This file contains all of the code and image processing methods used to train the model.
dataset_create.py: This script creates the positive and negative case folders and names the photos according to the specifications.

For reference, test case photos for both categories were provided to the repository together with the terminal output.

Libraries
Python3 , OpenCV - cv2 , pickle , datafile libraries 

Output
Positive case

![cancer image](https://user-images.githubusercontent.com/33830482/42348966-c8301910-80c8-11e8-9427-34fba3c0b84c.png)
![cancer terminal](https://user-images.githubusercontent.com/33830482/42348967-c92cb17a-80c8-11e8-82df-c31cba6ac42a.png)

Negative case

![no cancer image](https://user-images.githubusercontent.com/33830482/42348968-c95ed394-80c8-11e8-8c2e-5f25a61f3ccd.png)
![no cancer terminal](https://user-images.githubusercontent.com/33830482/42348970-c9da984e-80c8-11e8-87e0-4afe7dde8bfb.png)


