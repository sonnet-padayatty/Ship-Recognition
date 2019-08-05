# AV's Game of Deeplearning (Hackathon)

# Competion link: 
https://datahack.analyticsvidhya.com/contest/game-of-deep-learning/

# Ship-Recognition
Identifying the type of ship images by Deep Learning Techniques

# Problem Description
Ship or vessel detection has a wide range of applications, in the areas of maritime safety, fisheries management, marine pollution, defence and maritime security, protection from piracy, illegal migration, etc. Keeping this in mind, a Governmental Maritime and Coastguard Agency is planning to deploy a computer vision based automated system to identify ship type only from the images taken by the survey boats. You have been hired as a consultant to build an efficient model for this project. There are 5 classes of ships to be detected which are as follows:
1. Cargo
2. Tanker
3. Military
4. Carrier
5. Cruise
# Dataset Description
There are 6252 images in train and 2680 images in test data. The categories of ships and their corresponding codes in the dataset are as follows -
'Cargo' -> 1
'Military' -> 2
'Carrier' -> 3
'Cruise' -> 4
'Tankers' -> 5
There are three files provided to you, viz train.zip, test.csv and sample_submission.csv which have the following structure.

Variables	        Definition
1. image	        Name of the image in the dataset (ID column)
2. category	      Ship category code (target column)

# Evaluation Metric
The Evaluation metric for this competition is weighted F1 Score.

# Public and private dataset splitting
Public leaderboard is based on randomly selected 30% of the test images, while private leaderboard will be evaluated on remaining 70% of the test images.

# Python Libraries
keras,numpy,pandas,listdir,isfile,join

# Approach
Created a Sequential model using Keras library
Tried different models using various techniques like
1. pre-trained architectures (resnet/NASNetLarge)
2. diffrent image sizes
3. data augmentation

# Secured Rank in the Competition
246 out of 2083

# Conclusion
Due to the limitation of GPU and RAM specifications, it is not realistic to implement fast.ai or any other pre-trained architectures. If someone has great hardware specifications demamded by deep learning / or the access to deep learning cloud infra provided by AWS/ Azure / Google cloud, it is possible to increase the accuracy of the model upto 99%. 

Better models can be created only by better machines. 
