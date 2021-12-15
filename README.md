
# Ransomware-Transactions-Detection

### Problem Statement:
Build a classification  model to detect whether the bitcoin transaction is  a ransomware attack or not.

### Dataset:
The dataset is provided by UCI. It has  2,916,697 records with 10 features like the bitcoin transaction address and date. 
Each row represents a transaction. The target is the label of the transaction: Is it a ransom transaction or not?<br><br>

#### Full data
It can be accessed from here: [Full data](https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset)

#### Best model data:
The data is too big to upload in github, but you can [download it from here](https://drive.google.com/file/d/160KSNgXVwATn1EBSE1MwM5v44_DM8Pai/view?usp=sharing).

### Model Score:
#### Data:
Undersampled (with TomekLinks and EditedNearestNeighbours) and unbalanced, scaled with min-max<br>
#### Model:
AdaBoosting with XGB, GBT and GNB
#### Scoring:
![CM](https://raw.githubusercontent.com/SDAIA-T5-Projects/Ransomware-Transactions-Detection/main/Photo/CM.png)
![AUC](https://raw.githubusercontent.com/SDAIA-T5-Projects/Ransomware-Transactions-Detection/main/Photo/AUC.png)

Accuracy   =  0.9118<br>
Precision  =  0.896 <br>
Recall        =  0.9319 <br>
F-Score       =  0.9136<br>
AUC           = 0.97


### Recommendations:

For future work, we recommend collecting more updated data with more significant features like the time and targeted company information.



