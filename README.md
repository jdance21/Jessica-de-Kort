# Jessica-de-Kort

Import the test files from Processed Data folder
Load the U-Net Model
Define the Dice Coefficient 
Define the Focal Loss Function
Go through every slice of testing_segmentation_data and testing_ultrasound_data
Compile, load and predict the dice coefficient using the u-net model with a threshold of 0.5 on the predicted segmentation which is testing_ultrasound_data
Calculate and print the Mean Dice Coefficient 
