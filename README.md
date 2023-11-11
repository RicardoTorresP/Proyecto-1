# Proyecto-1 librerias:

import pandas as pd

import os
from datetime import datetime
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import chi2_contingency
import numpy as np
from itertools import combinations
from sklearn.preprocessing import FunctionTransformer
from sklearn.impute import SimpleImputer
from pandas.api.types import is_string_dtype
import re

from sklearn.compose import ColumnTransformer,make_column_selector
from sklearn.preprocessing import FunctionTransformer, MinMaxScaler,PowerTransformer
from sklearn.pipeline import Pipeline
from sklearn.decomposition import PCA
from sklearn.cluster import KMeans
from sklearn.preprocessing import LabelEncoder

from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
from sklearn.ensemble import IsolationForest
from sklearn.svm import OneClassSVM
import shutil
