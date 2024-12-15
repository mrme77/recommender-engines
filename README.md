# Reccomender Engine
![Image](reccomender_picture.png)

###  **Overview:**
This project analyzes user's interaction with articles  on the IBM Watson Studio platform, and make reccomendation to them about new aritcles that we believe they will like. To be continued...

### Prerequisites

1. Git
2. Python 3.7+ (3.11+ preferred)
3. VS Code Editor (or any other IDE)


The following modules are required: 
```
import numpy as np
from tqdm import tqdm
import sqlite3
import pandas as pd
import seaborn as sns
import joblib
import re
import sys
import pickle
import warnings
from nltk.tokenize import word_tokenize
from sklearn.model_selection import cross_val_score
from sklearn.multioutput import MultiOutputClassifier
from sklearn.metrics import accuracy_score, precision_score, recall_score, classification_report
from nltk.stem import WordNetLemmatizer
from sklearn.pipeline import Pipeline
from sklearn.metrics import confusion_matrix
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.feature_extraction.text import CountVectorizer, TfidfTransformer
from sklearn.model_selection import GridSearchCV
from sklearn.linear_model import LogisticRegression
warnings.filterwarnings('ignore')
pd.set_option('display.max_colwidth',True)
```
### Deployment
### Resources
-
-
### Outputs

Below are 2 screenshots displaying the web application.

### Acknowledgment
I would like to acknowledge to Stackoverflow, You.com for its generative AI models, and ChatGPT as an instrumental aid in the development of this project.
