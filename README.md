# 介紹  
本專案使用kaggle提供之鐵達尼資料，透過多種機器學習方法預測乘客是否存活，同時建立小遊戲，透過您輸入的資料來預測是否存活。

# 使用套件
import pandas as pd  
import matplotlib.pyplot as plt  
import numpy as np  
from sklearn import tree, datasets  
from sklearn.model_selection import train_test_split  
from sklearn.preprocessing import StandardScaler  
from sklearn.linear_model import LogisticRegression  
from sklearn.neighbors import KNeighborsClassifier  
from sklearn.svm import SVC  
from sklearn import metrics  
from sklearn.naive_bayes import GaussianNB, MultinomialNB, BernoulliNB  
from sklearn.tree import DecisionTreeClassifier  
from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier  
from sklearn.metrics import confusion_matrix, roc_auc_score  
from scipy.stats import wilcoxon  
from statsmodels.stats import multitest  
import rpy2.robjects as robj  
from rpy2.robjects.packages import importr  
