# ODD2023-DataScience-Ex-03
## AIM:
To read the given data and perform the univariate analysis with different types of plots.

## ALGORITHM:
STEP 1:
Read the given data.

STEP 2:
Get the informations and type of datas.

STEP 3:
Count the values using value_counts().

STEP 4:
Describe the dataframe.

STEP 5:
Do plots like boxplots,countplot,distribution plot,histogram plot.

## PROGRAM:
Developed by: KEERTHANA S
Reference number:212222230066
# diabetes.csv
```c
import pandas as pd
df=pd.read_csv("/content/diabetes.csv")
df
df.info()
df.dtypes
df['DiabetesPedigreeFunction'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='SkinThickness',data=df)
sns.countplot(x="SkinThickness",data=df)
sns.distplot(df['SkinThickness'])
sns.histplot(x="SkinThickness",data=df)
df.skew()
sns.histplot(x='Insulin',data=df)
sns.distplot(df['BloodPressure'])
df.kurtosis()
sns.boxplot(x='Insulin',data=df)
sns.boxplot(x='SkinThickness',data=df)
```
# employeesal.csv
```c
import pandas as pd
df=pd.read_csv("/content/employeesal.csv")
df
df.info()
df.dtypes
df['Salary'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Experience_Years',data=df)
sns.countplot(x="Experience_Years",data=df)
sns.distplot(df['Experience_Years'])
sns.histplot(x="Experience_Years",data=df)
df.skew()
sns.histplot(x='Salary',data=df)
sns.distplot(df['ID'])
df.kurtosis()
sns.boxplot(x='Salary',data=df)
sns.boxplot(x='Experience_Years',data=df)
```
# SuperStore.csv
```c
import pandas as pd
df=pd.read_csv("/content/SuperStore.csv")
df
df.info()
df.dtypes
df['Sales'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Postal Code',data=df)
sns.countplot(x="Postal Code",data=df)
sns.distplot(df['Postal Code'])
sns.histplot(x="Postal Codes",data=df)
df.skew()
sns.histplot(x='Sales',data=df)
sns.distplot(df['Postal Code'])
df.kurtosis()
sns.boxplot(x='Sales',data=df)
sns.boxplot(x='Row ID',data=df)
```

## OUTPUT:
### For diabetes.csv file
### Data frame
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/21bf0868-3b0b-4e1d-9e2a-cabf58ff9f69)

### Data information
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/f8a997ad-14ab-410b-af5b-cab05d528b70)

### Data type and value_count
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/72a238aa-f445-4051-baeb-245f5b71dfc8)

### Describing a data
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/85fae1ef-e104-479c-8337-e368eaa81913)

### Boxplot
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/6c208f3a-2ca5-4f0f-8c13-d17964abaa7c)

### Countplot
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/7599d03b-6d6d-4dcb-808d-f83bccfbe803)

### Distribution plot
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/786a91e8-8c4b-4ab3-a904-f56fb9da4dcb)

### Histogram plot
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/5a7f604f-1200-439f-9a25-e906f8e5e746)

### Skewness
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/5e9ef492-7e46-4446-8a27-1a1f364586e4)

![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/43c34783-0edb-4946-bd2f-c6a621efbd34)

![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/b67314c0-e6c7-4d55-8363-52d33b860dc6)

### Kurtosis
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/09f438e8-37ae-4a0d-a672-048308d83799)

![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/59cab2fd-2a1f-49ba-be8e-8b6ebb571178)

## For employeesal.csv file
### Data frame
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/09e10570-d18d-44a0-a353-7244a3e58bdd)

### Data information
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/d7564ee8-13ae-4466-8be3-7de626855fd2)

### Data type and value count
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/3827657c-aa15-4e1c-adf5-45007f1e6c2a)

### Describing a data
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/8b6129b2-3a63-45a3-a29c-bb2159ec9346)

### Boxplot
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/2a53749f-965a-466c-b85f-6640562dafc9)

### Countplot
![image](https://github.com/Keerthanasampathkumar/ODD2023-DataScience-Ex-03/assets/119477890/89ca409a-e728-4468-8fb8-32190a40c6ca)

### Distributionplot












