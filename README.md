# COVID19-Probability-Symptoms-Checker

![](https://img.shields.io/github/languages/code-size/iSumitBanik/COVID19-Probability-Symptoms-Checker?style=flat-square) ![](https://img.shields.io/github/stars/iSumitBanik/COVID19-Probability-Symptoms-Checker?style=flat-square) ![](https://img.shields.io/github/last-commit/iSumitBanik/COVID19-Probability-Symptoms-Checker?style=flat-square) ![](https://img.shields.io/github/followers/iSumitBanik?style=flat-square)

### Problem Setup
We all know, as the cases count are increasing day by day bulk testing isn't getting feasible and faster at this rate. This inspired me to create a probabilistic analysis whether a person is infected or not keeping in mind with the list of symptoms as said by the World Health Organization (WHO). 👨🏻‍⚕️

### Datasets

1. [Patient Medical Data for Novel Coronavirus COVID-19](https://datarepository.wolframcloud.com/resources/Patient-Medical-Data-for-Novel-Coronavirus-COVID-19)
2. [Cleaned Dataset](https://github.com/iSumitBanik/COVID19-Probability-Symptoms-Checker/raw/master/COVID-19/covid_final_data.csv)

### Features

| Attributes  | Description |
|     :---:      |     :---:      |
| Age  | Patient Age  |
| Gender  | Patient Gender (Female=0/Male=1)  |
| Location | Patient is from COVID-19 affected area or not (No=0/Yes=1) |
| Fever |Patient Fever (No=0/Yes=1) |
| Dry Cough  |Patient Dry Cough (No=0/Yes=1) |
| Fatigue |Patient Fatigue (No=0/Yes=1) |
| Pains | Patient Pains (No=0/Yes=1)|
| Nasal Congestion |Patient Nasal Congestion (No=0/Yes=1) |
| Problem in Breathing | Patient Breathing Problem (No=0/Yes=1)|
| Sore Throat | Patient Sore Throat (No=0/Yes=1)|
| Headache |  Patient Headache (No=0/Yes=1)|
| Vomiting | Patient Vomiting (No=0/Yes=1) |
| Runny Nose | Patient Runny Nose (No=0/Yes=1) |
| Diarrhea | Patient Diarrhea (No=0/Yes=1) |

### Choice of Model

The model used for probabilistic analysis for COVID-19 infection is **Logistic Regression**
*  Why is Logistic Regression preferred over other models?
<br><br>No algorithm is generally the best one but in this case, as the output of this problem statement will give either Yes/No, so LR is preferred for Binary Classification. On the other hand, tree based approach were much slower and accuracy is lower than LR.

### Notebook:
Check the notebook for the detailed analysis, [here](https://github.com/iSumitBanik/COVID19-Probability-Symptoms-Checker/blob/master/COVID19%20Symptoms%20Prediction.ipynb) 

### Visual Representations:
![](https://raw.githubusercontent.com/iSumitBanik/COVID19-Probability-Symptoms-Checker/master/images_analysis/SC_1.png)
![](https://raw.githubusercontent.com/iSumitBanik/COVID19-Probability-Symptoms-Checker/master/images_analysis/SC_2.png)
![](https://raw.githubusercontent.com/iSumitBanik/COVID19-Probability-Symptoms-Checker/master/images_analysis/SC_3.png)

#### Social Media
Follow me on [Twitter](https://twitter.com/TheSumitBanik)
