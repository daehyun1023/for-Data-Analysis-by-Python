import os
from os import chdir
chdir('/Users/jihyun/Desktop/postech/bigdata
os.getcwd()

import numpy as np
import pandas as pd
import statsmodels.api as sm
import seaborn as sns

from sklearn.preprocessing import scale,robust_scale,minmax_scale
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import confusion_matrix
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score

np.random.seed(42)

# 맷플롯립 설정
%matplotlib inline
import matplotlib
import matplotlib.pyplot as plt
plt.rcParams['axes.labelsize'] = 14
plt.rcParams['xtick.labelsize'] = 12
plt.rcParams['ytick.labelsize'] = 12

# 한글출력
matplotlib.rc('font', family='AppleGothic')
plt.rcParams['axes.unicode_minus'] = False

# warnings 
import warnings
warnings.filterwarnings('ignore')
