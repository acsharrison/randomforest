# randomforest

Link to youtube demo: https://www.youtube.com/watch?v=XkaFG-DWlf8

** Ran on Jupyter Notebook

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_absolute_error
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
from sklearn.model_selection import GridSearchCV
!pip install graphviz
