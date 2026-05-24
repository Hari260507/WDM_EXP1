### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name string
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
mylu,101,high,5,female,12345
muthu,102,high,10,male,56789
maha,103,medium,3,female,890846
mila,104,medium,2,female,753728

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temperature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,89.0,false,yes
rainy,90.0,89.0,true,yes
overcast,87.0,84.0,false,no
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

<img width="1225" height="735" alt="Screenshot 2026-01-23 155040" src="https://github.com/user-attachments/assets/17d82a3a-e745-443e-95d4-3e5556f92942" />

<img width="1230" height="737" alt="Screenshot 2026-01-23 155819" src="https://github.com/user-attachments/assets/917dc757-599e-4960-9d4c-542a23c5c88a" />



### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

<img width="1230" height="739" alt="Screenshot 2026-01-23 155115" src="https://github.com/user-attachments/assets/db78c095-bc93-46dc-a239-86d01866c8cc" />

<img width="1232" height="746" alt="Screenshot 2026-01-23 155854" src="https://github.com/user-attachments/assets/e19ead18-1632-4d08-b307-b9b97e04f5db" />


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

<img width="1230" height="731" alt="Screenshot 2026-01-23 155217" src="https://github.com/user-attachments/assets/b411e995-af70-4b33-bdfb-6c55f0a8f28b" />

<img width="1234" height="744" alt="Screenshot 2026-01-23 155924" src="https://github.com/user-attachments/assets/33d0cf35-e61e-46a4-91b9-adad165439aa" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

<img width="1226" height="745" alt="Screenshot 2026-01-23 155252" src="https://github.com/user-attachments/assets/916b9141-1956-4c69-baae-3dd38637acc1" />

<img width="1232" height="743" alt="Screenshot 2026-01-23 155943" src="https://github.com/user-attachments/assets/0980edc1-677c-4e8f-9e6b-5900fab87631" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
