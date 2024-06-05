# Satellite Land Use Classification

Satellite images are often use for survey of land area sureveys. However manual classification of thease images is a challenging task due to large number of images in a dataset.

For accurate classification of thease images, I have created and compared various deep learning architehtures as well as pre-trained models for their feasability in this task.

--- Models Used ---    
ResNET-50 Custom Trained     

ResNET-50 Pretrained

VGG-19 Pre-trained

MobileNET-V2 Custom Trained

--- Dataset ---              
Data is obtained from EuroSAT Dataset containing 27000 images from Sentinel-2 Satellite classifed and tagged into 10 categories as follows :-

<img src = 'https://github.com/phelber/EuroSAT/blob/master/eurosat-overview.png?raw=true' height = 250px width = 500px>


--- Performance Summary ---                                     
 
    1) ResNET-50 custom trained:-                     
    - Trained a ResNET-50 model from scratch using Tensorflow on  Apple M1 Metal GPU.      
    - Acheived an accuracy of 90% on training and 80.5% on test over 20 epochs of training.

    2) ResNET-50 pretrained:-
    - Trained ResNET-50 model based on pre-trained weights of ResNET50 model on Tensorflow.
    - Retrained the BatchNormalisation layers and a Dense Network for the classification model.
    - Acheived an accuracy of 98.3% on training and 97.8% on Test over 5 epochs of training.

    3) VGG-19 pretrained:-
    - Used Pretrained VGG-19 model parameters to train the model.
    - Retrained the BatchNorm layers to fit according to data.
    - Acheived an accuracy of 80.06% over 10 epochs.

    4) MobileNET-V2 custom trained:-
    - Implemented the model architehture from scratch using Tensorflow.
    - Trained the model with a training accuracy of 79% over 10 epochs.

--- Analysis of Models ---
    
    1) ResNET-50 models offered the highest accuracy on the dataset however they had large 
    number of parameters making predictions slower and model is unfit for smaller devices.

    2) VGG-19 is a vast network and reuired significantly more training time and data as 
    compared to ResNET-50 models but has the ability to offer more accurate predictions with 
    less parameters.

    3) MobileNET-V2 is a light model more suitable for making the model more efficient 
    for mobile devices. However due to the less number of epochs in training due to 
    the device limitations, the full potential of the model was not extracted from this model.
