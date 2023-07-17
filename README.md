# Jessica-de-Kort

Import the test files from Processed Data folder. Load the U-Net model and define the dice coefficient and the focal loss function which I got from Nikki's code. Have the code go through every slice of testing_segmentation_data and testing_ultrasound_data. Compile, load and predict the dice coefficient using the u-net model with a threshold of 0.5 on the predicted segmentation which is testing_ultrasound_data. Lastly, calculate and print the mean dice coefficient. 
