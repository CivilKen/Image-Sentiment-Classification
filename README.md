# Image-Sentiment-Classification
The contents includes more than 20000 pictures with human faces in different emotion. The main objective is to differentiate those emotions using convolutional neural network. Seven categories are included, and all pictures are pre-labeled.
In this task, VGG-net and ResNet are both used to deal the problem. This task is also run on Colab platform, and all the data and model can be saved on google drive.
#
All the picture will be processed by ParseData.ipnb first. This step will do feature scaling and normalization to rescale the pixcels, and these data will be stored as datafrme for further analysis. The training process comes in. Both VGG and ResNet will read the dataframe mentioned earlier, train the model with thoes data, and save the model.
