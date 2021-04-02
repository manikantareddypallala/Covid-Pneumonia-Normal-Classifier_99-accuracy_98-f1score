# Covid-Pneumonia-Normal-Classifier_99-accuracy_98-f1score
This repossitory contains a deep learning model to predict  if a patient is suffering from covid or pneumonia or the person doesn't suffer from any of those disease using there chest X ray ,  I have used classical transfer learning method with  a state of the art pretrained model ( resnet200d ) as a backbone and fine tuned its final layers with some heacvy augmentaions . The model shows some excellent results with a 98% f1 score and 99% accuracy in a completely hidden dataset and for the convienence i have added grad cam so that we can see what model is seeing to predict . 

# Datasets [ Citations / credits ]
Train dataset :- 
The model is trained nd validated from these 3 datasets by stratifing the folds into 5 splits , the model is trained and validated using single fold and still perform excellent thanks to the datasets authors for providing these datasets 
https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

https://www.kaggle.com/bachrr/covid-chest-xray

https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

Test dataset:-
The model is tested from these 3 datasets 
https://www.kaggle.com/nabeelsajid917/covid-19-x-ray-10000-images
https://www.kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets
https://www.kaggle.com/tawsifurrahman/covid19-radiography-database
