# Optimization_with_Gradient_Centralization
## Welcome to the Final Project Folder

This folder contains three Python scripts essential for training, testing, and analyzing machine learning models. Below is a description of each script and instructions on how to use them:

### 1. Final_ML_Project (Main Training Script)
This script is responsible for training the machine learning model based on the optimizer specified by the user. To run this script, you'll need to provide the name of an optimizer. Here are the available optimizers (append 'gc' to the name for Gradient Centralization):

- gd
- sgd
- sgdgc
- sgdm
- sgdmgc
- rmsprop
- rmspropgc
- adam
- adamgc
- adagrad
- adagradgc

After selecting an optimizer, the script will train the model using the chosen optimizer and generate three output files:
   - **First file:** Model weights.
   - **Second file:** Training time per epoch.
   - **Third file:** Cost (output from the cost function).

To ensure the script runs correctly, execute it in the "Final_Project" folder.

### 2. Testing_model (Testing Script)
This script tests the trained model using the weights obtained from the "Final_ML_Project" script and the testing data set. It provides the accuracy of the model, allowing you to evaluate its performance.

### 3. Analysis (Analysis Script)
The "Analysis" script is designed for comparative purposes. It compares the training time between two types of optimizers:
   - Standard optimizer
   - Optimizer with Gradient Centralization

This analysis helps in understanding the performance improvements that gradient centralization may provide over standard optimization techniques.
