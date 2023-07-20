# Recognizing-Hand-Movements-Using-EEG-Signal-Classification
Using the following system architecture we managed to classify 6 different hand movements  (Forward, Backward, Left, Right, UP, Dawn)
for both the real movement and the imagery movement (Motor imagery)
* Paper can be found at  https://academic.oup.com/gigascience/article/9/10/giaa098/5918864#208064346 
and the dataset can be found at:https://ftp.cngb.org/pub/gigadb/pub/10.5524/100001_101000/100788/

* system architecture:

![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/cdee5992-f10e-4bc8-ace3-22aeb8a5b072)


* Methodology :

  we used 3 different feature extraction techniques
    1. Discrete wavelet transform (DWT)
    2. Common Spatial Pattern (CSP)
    3. Extracting statistical features

* we used different machine learning methods such as LDA, Random forest, and SVM.
Also, we used deep learning methods such as CNN, LSTM, and EEGNET architecture.

  EEGNET Architecture :
  
  ![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/4c72c7e8-16da-4d87-84b8-b0cbaefd9678)


* Results
  
  * The following Bar chart shows our results when classifying 6 movements for different subjects (`blue`) in comparison with the original Paper (`orange`)
![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/28d19713-e539-4761-bc75-e0c032bd3056)



  * The following line chart shows how the performance change when changing the number of classes for cross-subject results
    
    ![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/dcacf5fe-a68e-4460-8486-8255ed06c1ff)



* Deployment
  
  * we used Unity and Blender for creating a simulator for the movements.
  * The simulator can be found here: https://drive.google.com/file/d/1mrWMTimOA4dxspdH9cZ9dznV2-6pDoZW/view?usp=sharing

  ![image](https://github.com/MAbdelhamid2001/Recognizing-Hand-Movements-Using-EEG-Signal-Classification/assets/81767517/2acc8588-e955-4fef-8810-ef44c380d81e)

