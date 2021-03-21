Welcome to the sneak peek into my professional journey so far...

## About me
Started with biomedical engineering, witnessed usage of healthcare technology by clinicians across hospitals in South India. Pursuing masters in Digital health with a focus on data to get my hands dirty on coming up with meaningful innovation that serves the needs of healthcare.

## My projects
### **Data science**

#### Masters thesis- Detecting sepsis among ICU patients using machine learning- In progress
- Data pre-processing and mining from the [eICU database](https://eicu-crd.mit.edu/): A multi-center database comprising deidentified health data associated with over 200,000 admissions to ICUs across the United States between 2014-2015.
- Time series detection of Sepsis, which is a cause of 1 among 5 deaths worldwide according to the WHO 2020 report.
- Outcome variable Sepsis constructed by using the diagnosis string variable and by looking into ICD diagnosis codes.
- Patient based train test split to avoid information leakage
![] (/images/sep2.JPG)
- Tools used: Python,Pyspark, Google Bigquery, Spark SQL, Pandas, sklearn

#### [Pneumonia detection- AI in healthcare course project](https://github.com/arjun-subramaniyan/healthcare-ml/blob/main/Pneumonia_detection.ipynb)
- Kaggle challenge- 5863 Chest Xray images to detect fluid filling in the lungs
- Imbalanced dataset, accounted for using data augmentation, identified incorrect usage of vertical and horizontal flips on several notebook as that would create a bias in detection by placing the heart on the right side of the chest- A condition known as Dextrocardia
- Obtained test F1 score of 91.38 and an AUC score of 95.3
- Step by step code explained in [blog](https://ks-arjunsubramaniyan.medium.com/pneumonia-classification-in-x-rays-using-deep-learning-247d27ed1b6f)
![](/images/pne10.JPG)  ![](/images/pne11.JPG) 

#### [Sleep stage detection](https://github.com/arjun-subramaniyan/healthcare-ml/blob/main/EMGEOG_sleepstagetracker.ipynb)
- Data extracted from [Physionet challenge](https://physionet.org/content/challenge-2018/1.0.0/)
- Using Maachine learning and signal processing to detect the 3 stages of sleep- Awake, NREM, REM 
- EMG: Electrical activity in muscles which reduce upon deeper sleep and EOG: electrical activity elicited due to random movement of pupil(eyeball) which is highest during deep sleep stage(highest during REM phase)
- Leave one out cross validation used for training and XGboost algorithm gave an F1 of 80 on train set and 77 on unknown test set.
 ![](/images/sleep.PNG)



Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.







- 👋 Hi, I’m @arjun-subramaniyan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/arjunks95/Arjun_portfolio/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
