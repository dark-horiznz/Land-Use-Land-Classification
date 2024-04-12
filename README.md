# Land Use Land Classification
The Deep Learning Model for the LULC Level 2 Classification Problem statement. 
This Consists of a RESNet model to tackle the LULC Level 2 Classification Problem. The Model Architehture consits of Following Elements and Architehture.
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/e95fbe19-84fd-4147-9028-ba55512d80f6">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/0ec67afd-841a-4bc0-bce6-5c89dd36f9d8">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/0fc87bbe-286a-4088-b4d9-f71ae9e16fea">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/2ee551f9-0415-40ff-9470-1d7b4a329a88">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/fdbacb40-263e-44e0-bff2-0b0379511217">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/3383ee97-ad1e-452e-b160-6cd6d34ec0c0">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/e2824623-ac6c-47cc-b46b-e9c309868731">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/2ed8935a-fc70-47f0-ae7d-eb6a368718b7">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/09c07666-c228-4980-ac97-1d4f81d26b24">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/aac7b45d-eee5-41e2-be24-f37c7f59953c">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/77dd98b4-5f19-413c-ab82-cd8096abbae5">
<img width="824" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/baae494b-2797-4ed4-9dd6-c841701c63a2">
<H3>Results On Training</H3>
After Training the Model on the Sentinal-2 Dataset Obtained from Kaggle EuroSAT classification for initial Training of Parameters which consists of 23,555,082 induvidual trainable parammeters of this Deep Neural Network, We obtained the following test results of ROC Curve:-

<img width="357" alt="image" src="https://github.com/dark-horiznz/SIF-Space_Hackathon_2023/assets/141896962/7fc812fe-1a3b-46ea-997d-365ed6719ba8">

However we could not process the provided .TIF Images in time to reconvert them inorder to train the model on local image Datasets. Still this model after being trained on 27000 (64,64) size images of labelled land use instances which are corectlly labelled as per the provided specifications. We have obtained a Test accuracy of 89.78% on this initial training phase which will be further improved given further time for training on the Seasonal Data-Set Provided
