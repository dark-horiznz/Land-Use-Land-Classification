# Land Use Land Classification
The Deep Learning Model for the LULC Level 2 Classification Problem statement. 
This Consists of a RESNet model to tackle the LULC Level 2 Classification Problem. The Model Architehture consits of Following Elements and Architehture.
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/e95fbe19-84fd-4147-9028-ba55512d80f6">
<H3>Results On Training</H3>
After Training the Model on the Sentinal-2 Dataset Obtained from Kaggle EuroSAT classification for initial Training of Parameters which consists of 23,555,082 induvidual trainable parammeters of this Deep Neural Network, We obtained the following test results of ROC Curve:-

<img width="357" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/7fc812fe-1a3b-46ea-997d-365ed6719ba8">

However we could not process the provided .TIF Images in time to reconvert them inorder to train the model on local image Datasets. Still this model after being trained on 27000 (64,64) size images of labelled land use instances which are corectlly labelled as per the provided specifications. We have obtained a Test accuracy of 89.78% on this initial training phase which will be further improved given further time for training on the Seasonal Data-Set Provided
