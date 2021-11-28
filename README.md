# Image-Classification-and-ResNET-from-scratch

*****STEPS TO RUN THE CODE*********

All of the required code blocks are included in the notebook and are generally sorted in a way to be run 
sequentially. This readme explains the flow of the code in the notebook:

Please Note: The path provided fo training and testing sets in the KaggleModel.ipynb notebook should be replaced as per the location in the local Google Drives.

Testing CNN model for Kaggle Competition: [KaggleModel.ipynb]

	* Import necessary libraries [Cell 1]
	* Upload the train.csv and test.csv files and read the pickel files using Dataset [Cell 2]
  
	1. Run Cell 3 to read the training set and test set from PKL files. This cell will also split the training set into train and validation set.
	2. Run Cell 4 if the model is to be trained on entire training dataset. Otherwise, skip.
	3. Run Cell 5 to build the modified ResNet network.
	4. Run Cell 6 for training the model using training set.
	5. Running Cell 7 and 8 will generate the Loss vs #epochs and Accuracy vs #epochs graphs.
	6. Run Cell 9 to generate predictions for test set.
	7. Run Cell 10 to normalize the predictions to correct class labels.
	8. Run Cell 11 to generate a dataframe and download the predictions CSV file.
	9. Run Cell 12 to generate the architectural representation of the model.
