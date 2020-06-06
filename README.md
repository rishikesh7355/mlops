# MLOPS project : machine learning + operations 

*In this project we are training our ML model automatically i.e. from pulling the codes ,training ,testing and monitoring will be done via git,github,docker,jenkins and linux.*

>>> Requirements : ML,Docker,linux ,git,github,and jenkins commands and knowledge required .

dockerfile :used for creating image with ML libraries installed image is provided

 _creating jobs via jenkins_
 
 Job 1: pull the Github repo automatically when some developers push the codes
 
 Job 2:By searching into the code ,jenkins should automatically start the ML image conatainer and start training the model 
 i.e if it will be CNN code then jenkins start training the CNN code similary with Sklearn or other ML codes 
 
 Job 3:Train the model and check accuracy
 
 Job 4: if accuracy is less than 80% then tweak the model architechture .This can be done by adding more epochs ,layers etc through programming 
  
Job 5. Retrain and notify the developer that best model is created 

Job 6: monitor the jobs if fails then it should automatially start the container again from last trained model

