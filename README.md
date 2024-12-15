# Reccomender Engine
![Image](reccomender_picture.png)

###  **Overview:**

This project focuses on developing a recommendation system by analyzing user's interaction with articles  on the IBM Watson Studio platformform. Through a comprehensive approach, the analysis encompasses multiple recommendation techniques, including rank-based recommendations, user-user collaborative filtering, and matrix factorization. Beginning with exploratory data analysis to understand user behavior patterns, the project progresses through increasingly complex recommendation methodologies. While content-based recommendations are explored as an additional feature, the core emphasis remains on leveraging user interaction data to generate accurate and relevant article suggestions. The ultimate goal is to enhance user engagement by connecting readers with articles that align with their interests, creating a more personalized and engaging experience.

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
