# titanic-tree-ensemble-analysis
## Description
The performance of different ensemble methods was evaluated on the given dataset. The accuracy results for each method were as follows:

Bagged Tree Accuracy: 80.45% Random Forest Accuracy: 82.68% Boosted Tree Accuracy: 80.45% Best Random Forest Accuracy: 82.12% (with parameters: max_depth = 10, n_estimators = 50) Among the methods tested, the Random Forest classifier achieved the highest accuracy at 82.68%, indicating its superior ability to generalize on the dataset. The Boosted Tree and Bagged Tree methods both showed comparable performance, each with an accuracy of 80.45%.

The optimal parameters for the Random Forest were found to be a maximum depth of 10 and 50 estimators, resulting in an accuracy of 82.12%. This indicates that the Random Forest model can further improve performance when appropriately tuned.

In summary, the Random Forest method proved to be the most effective ensemble technique for this dataset, providing the highest accuracy and demonstrating the importance of parameter tuning in achieving optimal model performance.


## Table of Contents
- [titanic-tree-ensemble-analysis](#titanic-tree-ensemble-analysis)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
- [for visualisation](#for-visualisation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Credits](#credits)
  - [Tests](#tests)
  - [Questions](#questions)

## Installation
import pandas as pd
from sklearn.model_selection import train_test_split, GridSearchCV
import numpy as np
from sklearn.datasets import load_iris
from sklearn.tree import DecisionTreeClassifier
from sklearn import tree
#from sklearn.metrics import confusion_matrix, f1_score, precision_score, recall_score
from sklearn.ensemble import BaggingClassifier, RandomForestClassifier, GradientBoostingClassifier, AdaBoostClassifier
from sklearn.metrics import accuracy_score
# for visualisation
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn.tree import export_graphviz
from IPython.display import Image  
from subprocess import call


## Usage

The repository can be accessed using this link:https://github.com/Mikemupararano/titanic-tree-ensemble-analysis.

## License
This application is covered under the MIT license.
![License](https://img.shields.io/badge/license-MIT-blue.svg)
## Contributing
 N/A

## Credits
N/A
## Tests
N/A

## Questions
For any questions or concerns, please contact me at [kudath@yahoo.co.uk](mailto:kudath@yahoo.co.uk).
You can also find me on GitHub: [https://github.com/Mikemupararano](https://github.com/https://github.com/Mikemupararano)
