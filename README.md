# Investigation of EEG Waveforms that Characterize Traumatic Events
## Determining which EEG brain waves classify traumatic events using ML algorithms, principle component analysis, feature selection, and temporal data reduction. 

Many Emergency Department (ER) workers are consistently exposed to high-stress environments. These conditions can lead to long term mental health issues, including Acute Stress Disorder (ASD) and even Post-Traumatic Stress Disorder. To examine the affect of stress on the human brain, brain wave data is extracted using a mobile electroencephalography biomonitoring device. We develop a multiclassification algorithm that can predict the level of trauma at a given instance with over 90\% accuracy. Additionally, Principal Component Analysis (PCA) is performed to drastically reduce data size while maintaining accuracy.

To determine the extent to which we should reduce the data, we calculate the percentage of energy explained by different $k$ number of nodes. 

We compare the accuracy of 5 different classifiers: 
1. Ridge Regression
2. Supoort Vector Machines
3. Artificial Nueral Network
4. Linear Discriminant Analysis
5. K-nearest nieghbor

### Brain wave time series for one participant

<img width="872" height="560" alt="Screenshot 2025-08-04 at 5 24 38 PM" src="https://github.com/user-attachments/assets/77ca91ec-632a-468e-927e-e64969b77bff" />


### Distribution of events for the test set (left) and train set (right) 
<img width="619" height="234" alt="Screenshot 2025-08-04 at 5 18 58 PM" src="https://github.com/user-attachments/assets/31d71bde-5a45-45bd-b1c5-0da1e3ca718a" />

### Reducing data while maintaining energy 
<img width="615" height="337" alt="Screenshot 2025-08-04 at 5 18 29 PM" src="https://github.com/user-attachments/assets/c786074d-fc11-485a-bf67-5fcdbd57f305" />

### KNN Model Performance
<img width="587" height="294" alt="Screenshot 2025-08-04 at 5 18 21 PM" src="https://github.com/user-attachments/assets/49e45a6c-5ab1-4c8d-8a54-7fb0cdc8a7f2" />

### Classification Model Comparison
<img width="728" height="660" alt="Screenshot 2025-08-04 at 5 17 29 PM" src="https://github.com/user-attachments/assets/58f7d694-ab76-45ee-a43d-dd6a84f672ab" />
