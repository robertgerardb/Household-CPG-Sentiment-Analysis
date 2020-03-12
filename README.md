# Household-CPG-Sentiment-Analysis
![](./visuals/00_slides/Slide1.PNG)
---
## Table of Contents:
[1.0 Directory Structure](#10-directory-structure)<br>
[2.0 Orientation](#20-orientation)<br>
[3.0 Software APIs Libraries Used](#30-software-apis-libraries-used)<br>
[4.0 Data Dictionary](#40-data-dictionary)<br>
[5.0 High Level Overview of Findings](#50-high-level-overview-of-findings)<br>
[6.0 Minimum Viable Product for Web Application](#60-minimum-viable-product-for-web-application)<br>
[7.0 Next Steps and Recommendations](#70-next-steps-and-recommendations)<br>
[8.0 Sources and Citations](#80-sources-and-citations)<br>
[9.0 Contact Info](#90-contact-info)<br>

---
## 1.0 Directory Structure
```
├── Household-CPG-Sentiment-Analysis
    ├── visuals
    ├── eddi_findings.pdf
    ├── README.md
    ├── initial_imports_cleaning_engineering.ipynb
    ├── master_df.csv
    ├── bar.ipynb
    └── foo.ipynb
```    
## 2.0 Orientation


#### 2.1 Hypothesis
There is high positive consumer sentiment towards using household goods that reduce waste and promote environmental sustainability


## 2.2 Executive Summary




## 2.3 Objectives


## 2.4 Constraints
foo

## 3.0 Software APIs Libraries Used

#### 3.1 Data Engineering, Analysis, and Collection
- Python3
- Jupyter
- Atom
- GetOldTweets3
- Pandas
- Numpy
- Dill

#### 3.2 Natural Language Processing (NLP) Preprocessing and Modeling
Text Preprocessing
- TFIDF Vectorizer (Best Param)
- Count Vectorizer
- NLTK
- Spacy
NLP Sentiment Analysis Models
scikit-learn
- Support Vector Machine (Best Param)
- Random Forest
- Multinomial Naïve Bayes
TensorFlow (Keras)
- Recursive Neural Network
vaderSentiment
- Sentiment Analyser

#### 3.3 Visuals
- Chartify
- Bokeh
- Matplotlib: Pyplot
- Seaborn
- Missingno
- Microsoft PowerPoint
- Adobe Acrobat

## 4.0 Data Dictionary

| Column | Description |
| --- | --- |
| **Zip** | Zip Code. |
| **Pop Rank** | Ordinal population size. 1 is the largest populated zip code, 2 is the second largest. |
| **XXXX Mean Median** | The aggregated average annual sale price from the zip code median sale prices. |
| **Hurricane Affected** | 1 if the zip code was impacted by Hurricane X according to FEMA, 0 otherwise. |
| **% Change After Hurricane** | Percentage difference in median zip sale price comparing the month preceding the storm to the month following the storm.|

## 5.0 High Level Overview of Findings
#### Hot colors indicate largest drops in median sale price after the hurricane
#### Cold colors indicate largest increases in median sale price after the hurricane

### 5.1 Hurricane Dorian focused on Florida
![Dorian Affected Zip Codes](./visuals/dorian_tableau.png)

#### Example Dorian impact
![Example Dorian impact](./visuals/dorian_matplotlib.png)

### 5.2 Hurricane Sandy focused on North East U.S.
![Sandy Affected Zip Codes](./visuals/sandy_tableau.png)

### 5.3 Hurricane Harvey focused on greater Houston, TX
![Harcey Affected Zip Codes](./visuals/harvey_tableau.png)

## 6.0 Minimum Viable Product for Web Application

#### Enter a zip code to see the summary statistics<br>
### 6.1 Home Page of Flask App <br>
![Flask Home Page](./visuals/flask_home.png)

### 6.2 Results Page of Flask App for Zip Code 77071 Houston (Median Sale Price dropped ~24.4% directly after Harvey)<br>
![Flask Home Page](./visuals/flask_results.png)

## 7.0 Next Steps and Recommendations
* foo

## 8.0 Sources and Citations
1. <a href="https://www.zillow.com/research/data/">Zillow Median Sale Price by Zip (CSV)</a>

2. <a href="https://www.zillow.com/browse/homes/tx/harris-county/">Zillow: Harris County, TX Zip Codes</a>



## 9.0 Contact Info
Robert Becotte - email: robert.becotte@gmail.com , github: robertgerardb <br>
