# EmotionDetection
As the name implies, In this project I worked on classifying a person's emotions using a facial image.
before jumping into learnings and results, I want to say that this was my first Neural Network project so some of the things might sound like they weren't the best options to make, but it was a learning experience that came a long way and resulted in having way better results in the projects that followed.

#Key Words
Neural Networks, LBP, MatLab, Transfer Learning, ResNet50, Classifier

#Results and Process
I was able to achieve up to 86% accuracy. 
Keep in mind the accuracy depends on the dataset used, I used the CK+ Dataset ( Extended Cohn-Kanade Dataset ), before that I was using another enormous dataset but it affected the accuracy overall when testing it on people outside the dataset, this was due to the data containing both pictures of real people and cartoon characters so you can see how bad that is, this lead to learning about DATA CLEANING, yet even after cleaning the data the results didn't improve that much when testing, therefore I opted into looking for a new data set ( CK+ ). The results I had at that point made me research more and stumble on Transfer learning and testing it too. Testing out using multiple classifiers, the Ensemble Method:Subspace had the best results according to my old report at the time.

#Important Note
Since I was a beginner at the time I only extracted the resulting model and a early version of the code that doesn't contain LBP but rather uses the resnet Feature Extraction and also uses SVM Classifier which is an earlier version of the code, I can't find the final version but this repo is just a proof of concept.
