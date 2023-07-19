# Recognizing-Hand-Movements-Using-EEG-Signal-Classification
Using the following system architecture we managed to classify 6 different hand movements  (Forward, Backward, Left, Right, UP, Dawn)
for both the real movement and the imagery movement (Motor imagery)
* Paper can be found at  https://academic.oup.com/gigascience/article/9/10/giaa098/5918864#208064346 
and the dataset can be found at:https://ftp.cngb.org/pub/gigadb/pub/10.5524/100001_101000/100788/

* system architecture:

![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/0bb04a50-2466-4f29-967e-5bbbd016e88b)

* Methodology :

  we used 3 different feature extraction techniques
    1. Discrete wavelet transform (DWT)
    2. Common Spatial Pattern (CSP)
    3. Extracting statistical features

* we used different machine learning methods such as LDA, Random forest, and SVM.
Also, we used deep learning methods such as CNN, LSTM, and EEGNET architecture.

  EEGNET Architecture :
  
  ![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/a4d2b148-f0ee-4c74-97be-58826af3db68)

* Results
  
  * The following Bar chart shows our results when classifying 6 movements for different subjects (`blue`) in comparison with the original Paper (`orange`)
![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/f506845c-3f64-484c-9465-35b812a7e392)


  * The following line chart shows how the performance change when changing the number of classes for cross-subject results
    
    ![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/38b15fc7-765b-4cda-aa77-584d12bd5509)


* Deployment
  
  we used Unity and Blender for creating a simulator for the movements


  ![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/52713888-e685-4dab-8f70-a81ad2bc7259)
