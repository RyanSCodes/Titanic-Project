# Titanic-Project

##Variable Descriptions:

csv Variable | Explanation
-------------|--------------
survival | Survival  &emsp; (0 = No; 1 = Yes)  
pclass        |  Passenger Class &emsp; (1 = 1st; 2 = 2nd; 3 = 3rd)  
name          |  Name  
sex            | Sex  
age            | Age  
sibsp          | Number of Siblings/Spouses Aboard  
parch          | Number of Parents/Children Aboard  
ticket         | Ticket Number  
fare           | Passenger Fare  
cabin          | Cabin  
embarked       | Port of Embarkation &emsp;(C = Cherbourg; Q = Queenstown; S = Southampton)  

##Special Notes:

Pclass is a proxy for socio-economic status (SES)  
 1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower

Age is in Years; Fractional if Age less than One (1)  
 If the Age is Estimated, it is in the form xx.5

With respect to the family relation variables (i.e. sibsp and parch)  
some relations were ignored.  The following are the definitions used  
for sibsp and parch.

Sibling: &ensp;  Brother, Sister, Stepbrother, or Stepsister of Passenger Aboard Titanic  
Spouse: &ensp;  Husband or Wife of Passenger Aboard Titanic (Mistresses and Fiances Ignored)  
Parent: &ensp;  Mother or Father of Passenger Aboard Titanic  
Child:  &ensp;  Son, Daughter, Stepson, or Stepdaughter of Passenger Aboard Titanic  

Other family relatives excluded from this study include cousins,  
nephews/nieces, aunts/uncles, and in-laws.  Some children travelled  
only with a nanny, therefore parch=0 for them.  As well, some  
travelled with very close friends or neighbors in a village, however,  
the definitions do not support such relations.

## Files

* Titanic-Project.ipynb - Data visualisation and trends
* Titanic-Project-ML.ipynb - Comparision of machine learning algorithms
* Titanic-Project-Naive-Bayes-Model.ipynb - NB test set prediction 
* Titanic-Project-Random-Forests-Model.ipynb - RF test set prediction
* Titanic-Project-SVM-Model.ipynb - SVM test set prediction
* Titanic_pred_*.csv - Passenger ID and predictions in csv format