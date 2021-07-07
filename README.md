# Description:  
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.  
The problem was first solved by using a RandomForestClassifier, then the score was compared with an ANN's score.  
# Feature explanation:  
```age``` - numeric  
```job``` - categorical  
```marital status``` - categorical  
```education``` - categorical  
```credit``` - categorical, whether the person has credit or not  
```balance``` - numeric, average yearly balance in euros  
```housing loan``` - categorical, whether the housing has loan  
```personal loan``` - categorical  
```contact``` - categorical, contact communication type  
```last contact day``` - numeric, last contact day of the month  
```last contact month``` - categorical  
```last contact duration``` - numeric  
```campaign``` - numeric, number of contacts performed during this campaign  
```pdays``` - numeric, number of days that passed by after the client was last contacted from a previous campaign  
```previous``` - numeric, number of contacts performed before this campaign  
```poutcome``` - categorical, outcome of the previous marketing campaign  
```subscription``` - categorical, target variable  
# Requirements:
```tensorflow==2.5.0```  
```matplotlib==3.4.1```  
```numpy==1.19.5```  
```pandas==1.2.3```  
```seaborn==0.11.1```  
```scikit-learn==0.24.1```
