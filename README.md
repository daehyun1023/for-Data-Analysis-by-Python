
디렉토리 설정    
import os    
from os import chdir    
chdir('C:/Users/ahndae/Downloads')    
os.getcwd()    

넘파이, 판다스 씨본, 스케일 설정    
import numpy as np    
import pandas as pd    
import seaborn as sns    
from sklearn.preprocessing import scale,robust_scale,minmax_scale    


맷프롯립 설정    
import matplotlib    
import matplotlib.pyplot as plt    


import scipy.stats as stats        
import statsmodels.api as sm        
from statsmodels.formula.api import ols        
from sklearn import metrics        

나눔고딕체설정    
matplotlib.rc('font',family="NanumBarunGothic")    

워닝메시지 제거    
import warnings    
warnings.filterwarnings('ignore')    





의사결정 모델 모듈 불러오기    
# sklearn.tree의 DecisionTreeClassifier    
from sklearn.tree import DecisionTreeClassifier    

sklearn.tree의 export_graphviz        
from sklearn.tree import export_graphviz    
import graphviz    

랜덤포레스트    
from sklearn.ensemble import RandomForestClassifier


데이터 분할 함수    
from sklearn.model_selection import train_test_split    

그래디언트 부스팅    
from sklearn.ensemble import GradientBoostingClassifier    



svb 패키지    
from sklearn.svm import SVC    
스케일 조정 패키지    
from sklearn.preprocessing import scale    

그리드 탐색 import    
from sklearn.model_selection import GridSearchCV    









