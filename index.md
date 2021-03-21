Welcome to the sneak peek into my professional journey so far...

## About me
Started with biomedical engineering, witnessed usage of healthcare technology by clinicians across hospitals in South India. Pursuing masters in Digital health with a focus on data for coming up with meaningful innovation that serves the needs of healthcare.

## My projects
### **Data science**

#### Masters thesis- Detecting sepsis among ICU patients using machine learning- In progress
- Data pre-processing and mining from the [eICU database](https://eicu-crd.mit.edu/): A multi-center database comprising deidentified health data associated with over 200,000 admissions to ICUs across the United States between 2014-2015.
- Time series detection of Sepsis, which is a cause of 1 among 5 deaths worldwide according to the WHO 2020 report.
- Outcome variable Sepsis constructed by using the diagnosis string variable and by looking into ICD diagnosis codes.
![](/images/sep2.JPG)
- Patient based train test split to avoid information leakage
- Tools used: Python,Pyspark, Google Bigquery, Spark SQL, Pandas, sklearn

#### [Pneumonia detection- AI in healthcare course project](https://github.com/arjun-subramaniyan/healthcare-ml/blob/main/Pneumonia_detection.ipynb)
- Kaggle challenge- 5863 Chest Xray images to detect fluid filling in the lungs
- Imbalanced dataset, accounted for using data augmentation, identified incorrect usage of vertical and horizontal flips on several notebook as that would create a bias in detection by placing the heart on the right side of the chest- A condition known as Dextrocardia
- Obtained test F1 score of 91.38 and an AUC score of 95.3
- Step by step code explained in [blog](https://ks-arjunsubramaniyan.medium.com/pneumonia-classification-in-x-rays-using-deep-learning-247d27ed1b6f)

![](/images/pne7.png) 

#### [Sleep stage detection](https://github.com/arjun-subramaniyan/healthcare-ml/blob/main/EMGEOG_sleepstagetracker.ipynb)
- Data extracted from [Physionet challenge](https://physionet.org/content/challenge-2018/1.0.0/)
- Using Maachine learning and signal processing to detect the 3 stages of sleep- Awake, NREM, REM 
- EMG: Electrical activity in muscles which reduce upon deeper sleep and EOG: electrical activity elicited due to random movement of pupil(eyeball) which is highest during deep sleep stage(highest during REM phase)
- Leave one out cross validation used for training and XGboost algorithm gave an F1 of 80 on train set and 77 on unknown test set.
 ![](/images/sleep.png)
 
#### [Robolang-BIOS](https://capstone.utu.fi/en-robolang-bios)
 - Team capstone project to study the application of social robots in language teaching.
 - My role to study the emotional response in subjects by analysing the biosignals namely EDA(Electrodermal activity), PPG(Photoplethysmogram) and pupillometric activity
 - Mock trial conducted and spikes in EDA observed during a conversational dialog with the Nao robot.
 ![](/images/robolang.jpg)
 
### **Biomedical engineering**

#### Application of infrared thermography for ophthalmic diagnosis
 - Infrared imaging of the eyes to study the Ocular surface temperature(OST) and it's relationship with glaucoma
 - Made use of MLX90614 non contact IR temperature sensor along with arduino for faster measurement
 - Obtained a negative correlation between OST and IOP.
 <p align="center">
  <src="/images/15.jpg">
</p>
 


#### [Low Cost automated nurse call system for improving patient care using LabVIEW](https://www.worldscientific.com/doi/10.4015/S1016237218500308)
- Mini project using ECG simulation and signal processing
- Application for step-down wards where the central nurse station and Code blue team could be simultaneously alerted in case of an arrhythmia 
 ![](/images/nc.png)
 

Tools:
 ![](/images/l1.png) 
 ![](/images/l2.png) 
 ![](/images/l3.png) 

### Contact me

- 👋 Hi, I’m @arjun-subramaniyan
- 📫 ks.arjunsubramaniyan@gmail.com
- 📞 +91-9952030524
- [My github](https://github.com/arjun-subramaniyan)

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

[GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


