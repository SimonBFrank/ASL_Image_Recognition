# ASL_Image_Recognition

Convolutional Neural Network model classifying American Sign Language letter images into their corresponding written English letters

## Functionality

## Required Packages

* tensorflow
* keras
* collections
* sklearn
* numpy
* matplotlib
* seaborn

## File Descriptions

### /Data/

Holds data acquired from classmates

### /Data_Acquisition/

Shows how data was merged and transformed into full dataset

### /Data_Preprocessing/

Assess data acquired and performs preprocessing

### /Final_Model/

### How to load and test a model:
1. Open test.py
2. Download the model from link and place it in the same directory as the notebook.
    * Use the best_model.h5 to test without unknowns.
    * Use the model_ec.h5 to test the model with unknowns.
3. Change the variables dataDir, labelsDir, and load_model_filepath to the filepaths of data, labels, and model respectively
    * To test the extra credit, use the TestEC function with the classifier object.
    * For example, replace the best_model.Test(Xtest, ytest) with best_model.TestEC(Xtest, ytest)
4. Run all the cells and look at the bottom for the result

### How to train a model
1. Open train.py
2. Import all the necessary packages by running the first cell.
3. Set all hyper parameter values.
4. Find the save_model_filepath variable and set it to the filepath where you want the model to be saved.
5. Call the train function with our classifer object to train the model. The train function takes in the training data and labels as well as the validation data and labels.

### /Selecting_Model/

Created multiple end-to-end machine learning pipelines that includes pre-processing, classification and evaluation on the ASL data set. Compare classifiers implemented and provide discussion as to why some out-perform others given the properties of the data set and the classifiers used.

### EEL4930_Report.pdf

IEEE report detailing the implementations, experiments, and results of the model built.

## Author

* Simon Frank
* linkedin.com/in/simon-frank/
* github.com/SimonBFrank/

## Collaborators

* Mitchel Hammack
* Colin Kubisiak
* Antonio Antonian