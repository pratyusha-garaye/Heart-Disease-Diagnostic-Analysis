## Heart Disease Diagnostic Analysis
#### Software used 
* Python with ML Libraries (Pandas, Seaborn, Matplotlib)
* VS Code developing environment

#### Features in the dataset
* There are 13 features in the dataset.
age: Person's age in years

sex: The person's sex (Male=1, Female=0)

cp: Chest pain experienced (typical angina=0, atypical angina=1, non-anginal =2, aymptomatic=3)

trestbps: The person's resting blood pressure (mm Hg)

chol: The person's cholestrol level (mg/dl)

fbs: The person's fasting blood sugar (true=1 is >120 mg/dl, else false=0)

restecg: Resting electrocardiographic measurement (normal=0, ST-T wave abnormality=1, showing probable/definite left ventricular hypertrophy)

thalach: The person's maximum heart rate achieved 

exang: Exercise induced angina

oldpeak: ST depression induced by exercise relative to rest

slope: The slope of the peak exercise ST segment

ca: Number of major vessels colours by fluoroscopy 

thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

### Description
* Loaded the diagnosis data using Pandas and performed EDA.
<img width="873" alt="Headers" src="https://github.com/pratyusha-garaye/Heart-Disease-Diagnostic-Analysis/assets/172596779/88f6bbf6-a211-4222-87df-56ecd5c12b75">

* Added columns to turn categorical variables into string values.
* Used Seaborn and Matplotlib libraries to visualize relationship between various attributes in the dataset.

![BP:Age](https://github.com/pratyusha-garaye/Heart-Disease-Diagnostic-Analysis/assets/172596779/f854b982-d303-4fdf-8fb4-5b6b9d9646c5)
![Age distribution](https://github.com/pratyusha-garaye/Heart-Disease-Diagnostic-Analysis/assets/172596779/1d679fd2-6fcb-44cc-8149-84dae341067c)
![Age-wise sex distribution](https://github.com/pratyusha-garaye/Heart-Disease-Diagnostic-Analysis/assets/172596779/411d3973-f045-4a37-84c0-9217b4c837ee)

* Plotted a heatmap of the correlation coefficients between variables to understand the effect of each attribute on deciding whether disease is present or absent. 

![heatmap of correlations](https://github.com/pratyusha-garaye/Heart-Disease-Diagnostic-Analysis/assets/172596779/8eff0ed8-63fe-4e70-80fb-761adc437506)

### Conclusion 

It was found that from the given the dataset, female patients were more likely to have the disease, and is most common in the age ranging between 29 and 54.

Disease diagnosis is the most positively affected for the following factors:

* Exercise Induced Angina is negative, for 69.61% of the patients and this factor 3 times more likely to cause the disease.
* Chest pain type is 1, for 89% of the patients having this category of chest pain and this factor 2.32 times more likely to cause the disease.
* Number of major blood vessels type is 0, for 74.29% of the patients having this category of major blood vessels and this factor 2.13 times more likely to cause the disease.
* Slope of the peak exercise ST segment type is 2, for 75.35% of the patients having this category of slope and this factor 2.09 times more likely to cause the disease.



