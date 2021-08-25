Welcome to the sneak peek into my quest for knowledge and innovation...

# About me
Biomedical engineer with data skills and healthcare domain expertise. Seeking to solve the unmet needs of healthcare by understanding user expectation, plugging the gaps and delivering meaningful products.
Started with engineering, witnessed usage of healthcare technology by clinicians across hospitals in South India. Completing Masters in Digital health with a focus on data for coming up with meaningful innovation that serves the needs of healthcare.

# My projects
## **Data science**

### Masters thesis- Detecting sepsis among ICU patients using machine learning- In progress
- Data pre-processing and mining from the [eICU database](https://eicu-crd.mit.edu/): A multi-center database comprising deidentified health data associated with over 200,000 admissions to ICUs across the United States between 2014-2015.
- Time series detection of Sepsis, which is a cause of 1 among 5 deaths worldwide according to the WHO 2020 report.
- Outcome variable Sepsis constructed by using the diagnosis string variable and by looking into ICD diagnosis codes.
![](/images/sep2.JPG)
- Patient based train test split to avoid information leakage
- Tools used: Python,Pyspark, Google Bigquery, Spark SQL, Pandas, sklearn

### [Pneumonia detection- AI in healthcare course project](https://github.com/arjun-subramaniyan/healthcare-ml/blob/main/Pneumonia_detection.ipynb)
- Kaggle challenge- 5863 Chest Xray images to detect fluid filling in the lungs
- Imbalanced dataset, accounted for using data augmentation, identified incorrect usage of vertical and horizontal flips on several notebook as that would create a bias in detection by placing the heart on the right side of the chest- A condition known as Dextrocardia
- Obtained test F1 score of 91.38 and an AUC score of 95.3
- Step by step code explained in [blog](https://ks-arjunsubramaniyan.medium.com/pneumonia-classification-in-x-rays-using-deep-learning-247d27ed1b6f)

<p align="center">
  <img src="/images/pne7.png"/>
</p>

### [Sleep stage detection](https://github.com/arjun-subramaniyan/healthcare-ml/blob/main/EMGEOG_sleepstagetracker.ipynb)
- Data extracted from [Physionet challenge](https://physionet.org/content/challenge-2018/1.0.0/)
- Using Machine learning and digital signal processing to detect the 3 different stages of sleep- Awake, NREM(Non rapid eye movement), REM (Rapid eye movement)
- EMG: Electrical activity in muscles which reduce upon deeper sleep and EOG: electrical activity elicited due to random movement of pupil(eyeball) which is highest during deep sleep stage(highest during REM phase)
- Leave one out cross validation used and XGboost algorithm gave an F1 of 80 and 77 on train and unknown test set.
<p align="center">
  <img src="/images/sleep.png"/>
</p>
 
### [Robolang-BIOS](https://capstone.utu.fi/en-robolang-bios)
 - Team capstone project to study the application of social robots in language teaching.
 - My role was to study the emotional response in subjects by analysing the biosignals namely EDA(Electrodermal activity), PPG(Photoplethysmogram) and pupillometric activity when the subjects had a conversation with the Robot.
 - Mock trial conducted and spikes in EDA observed during the conversational dialog.

<p align="center">
  <img src="/images/robolang.jpg"/>
</p>
 
## **Biomedical engineering**

### Application of infrared thermography for ophthalmic diagnosis
 - Infrared imaging of the eyes to study the Ocular surface temperature(OST).
 - Made use of MLX90614 non contact IR temperature sensor along with arduino for faster measurement
 - Obtained a negative correlation between OST and Intra-ocular pressure (IOP), a screening parameter for glaucoma.
<p align="center">
  <img src="/images/15.jpg"/>
</p>
 


### [Low Cost automated nurse call system for improving patient care using LabVIEW](https://www.worldscientific.com/doi/10.4015/S1016237218500308)
- Mini project using ECG simulation and signal processing
- Application for step-down wards where the central nurse station and Code blue team could be simultaneously alerted in case of an arrhythmia 
<p align="center">
  <img src="/images/nc.png"/>
</p>
 
 

### Tools:
 ![](/images/l1.png) 
 ![](/images/l2.png) 
 ![](/images/l3.png) 

---
### Contact me

👋 Hi, I’m on [Linkedin](https://www.linkedin.com/in/arjun-subramaniyan-ks/) |📫 ks.arjunsubramaniyan@gmail.com | 📞 +91-9952030524 |[My github](https://github.com/arjun-subramaniyan) |




