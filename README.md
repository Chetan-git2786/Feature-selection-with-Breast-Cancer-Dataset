## Feature Selection on the Breast Cancer Dataset

**Details about the project** :
                                This project was done with the objective to find out the most influential features available in the dataset that cause Breast cancer in women. enter image description here
   Breast cancer (BC) is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths according to global statistics, making it a significant public health problem in today’s society.
![enter image description here](https://github.com/Chetan-git2786/Feature-selection-with-Breast-Cancer-Dataset/blob/main/BC_Img1.png?raw=true)
    
  The early diagnosis of BC can improve the chance of survival significantly, as it can predict timely clinical treatment to patients. Further accurate classification of benign tumors can prevent patients undergoing unnecessary treatments. Thus, the correct diagnosis of BC and classification of patients into malignant or benign groups is the subject of much research. Because of its unique advantages in critical features detection from complex BC datasets, machine learning (ML) is widely recognized as the methodology of choice in BC pattern classification and forecast modelling.
  ![enter image description here](https://github.com/Chetan-git2786/Feature-selection-with-Breast-Cancer-Dataset/blob/main/BC_Img3.png?raw=true)
  
 The dataset has the data w.r.t  several features w.r.t the tumour such as radius,texture,perimeter,area,smoothness,concavity,compactness,concave points etc.,
 ![enter image description here](https://github.com/Chetan-git2786/Feature-selection-with-Breast-Cancer-Dataset/blob/main/BC_Img7.png?raw=true)
 
  Also performed feature selection with different methods like feature selection with correlation, univariate feature selection, recursive feature elimination (RFE), recursive feature elimination with cross validation (RFECV) and tree based feature selection. Random forest is used to classify in order to train our model and predict the tumour type.    

**Python Libraries Used :**
In this project, the python code was written by making use of the Python Libraries like Numpy, Pandas, Matplotlib, Seaborn to load the data & derive the insights in the form of a visualization on split basis of the tumour type 'Benign' or 'Malignant' 

  **Insight from Visualization:** 
     The information related to the most influential features that cause the "malignant tumour" have been figured out by deploying various "Feature selection techniques" .  
     
**Conclusion :** 
From the above visualization & the various feature selection methods , we can say that the features "radius_mean", texture_mean" are the most important factors to predict whether the Tumour is benign or Malignant

To check out the notebook, please [click](https://github.com/Chetan-git2786/Feature-selection-with-Breast-Cancer-Dataset/commit/ac2a8191487b302b85ed511dba1ad199edb06aa7) here

![enter image description here](https://github.com/Chetan-git2786/Feature-selection-with-Breast-Cancer-Dataset/blob/main/BC_Img2.png?raw=true)

