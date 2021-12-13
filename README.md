# SML310FinalProject
These are convolutional neural networks used in my final project in Princeton's SML310 course, where I trained neural networks to identify traffic signs from multiple countries using different methods.

Here are descriptions of what each program is:
## Individual_Learning_German
This is an example of individual learning, or training and testing a CNN on the same database. This program runs this process on the German GTSRB dataset. While I have done the same procedure on the Chinese TSRD dataset, the program is identical save for the database called, therefore uploading one is sufficient.

## Individual_Balancing
This program was used to rebalance the TSRD dataset, which was previously distributed unevenly across the given training and testing sets.

## Collaborative_Learning
The neural network was trained on a training set made up of a combination of the German and Chinese training sets, and the resulting model was then used to test classification accuracy on the German and Chinese testing sets separately.

## Personalized_Learning
This neural network was also trained on the combined training set, but the model was then retrained and tested using more images from the German and Chinese datasets separately to create models more specialized for classifying their respective datasets.

## Transfer_Learning
In this learning method, the neural network is first trained on one dataset, then retrained with the dataset that the CNN is intended to categorize. In this particular program, the pre-trained model is the one from Individual_Learning_German that has been imported for retraining and testing on the Chinese dataset. I have done this procedure in reverse, but I did not include the specific program as if would be redundant.
