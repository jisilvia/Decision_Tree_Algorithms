# Decision Tree Algorithms
<p align="center">
  <img width="auto" height="auto" src="https://www.explorium.ai/wp-content/uploads/2019/12/Decision-Trees-2.png">
</p>
A decision tree is a decision support tool that uses a tree-like model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.


# Project Description

This project aims to build various Decision Tree Classifier Models to predict the income group of people along with seven demographic variables: Age, Capital Gain/Loss, Education, Hours per Week, Marriage Status and Relationship, Occupation, and Race and Sex. Out of all decision trees, the best model is chosen, refined, and visualized. Subsequently, the model is automated and predictions are made for a new record.


## Steps

 1. Data Cleaning and Exploration
 2. Building Decision Tree Classifier Models
 3. Evaluating Tree Performance
 4. Automation
 5. New Prediction

## Requirements

**Python.** Python is an interpreted, high-level and general-purpose programming language. 

**[Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true).** Google colab is a free online Integrated Data Environment.

### Packages 
Install the following packages in Python prior to running the code.
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
from sklearn.externals.six import StringIO  
from IPython.display import Image  
from sklearn.tree import export_graphviz
import pydotplus
from sklearn.metrics import classification_report, confusion_matrix
from sklearn.metrics import roc_auc_score
from sklearn.metrics import roc_curve
from sklearn.metrics import accuracy_score
from sklearn.metrics import precision_score
from sklearn.metrics import f1_score
from sklearn.metrics import recall_score
from google.colab import drive
drive.mount('/content/drive')
```
After importing ```drive.mount('/content/drive')```, follow instructions in the output to authorize access to Google Drive in order to obtain directories.

## Launch

Download the data file provided and decompress it. Using Google Drive, create the following folder structure and upload the data here:

```
/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA02/Data
```

where ```/content/drive/MyDrive``` is the standard file path.

## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements

The project template and dataset were provided by [Arin Brahma](https://github.com/ArinB) at Loyola Marymount University.
