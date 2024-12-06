# Deep Learning-based Recommendation System-NCF(Neural-Collaborative-Filtering) Based
- A deep learning-based recommendation system that provides personalized suggestions using advanced algorithms

## Overview
This repository contains NCF(Neural-Collaborative-Filtering) based recommendation system that aims to provide personalized content suggestions using state-of-the-art algorithms.

## Dataset
- The Movies Dataset
- Metadata on over 45,000 movies. 26 million ratings from over 270,000 users.

The dataset consists of the following files:
- `credits.csv`
- `keywords.csv`
- `links.csv`
- `links_small.csv`
- `movies_metadata.csv` (used)
- `ratings.csv` (used)
- `ratings_small.csv`

For this project, we will be using:
- `ratings.csv`
- `movies_metadata.csv`

## Features
- User-based and item-based collaborative filtering
- Content-based filtering
- Hybrid recommendation strategies
- Evaluation metrics for performance analysis

## Required Libraries
To run this project, you need the following libraries:
```python
import pandas as pd
import numpy as np
import json
from sklearn.preprocessing import LabelEncoder
import torch
import torch.nn as nn
from torch.utils.data import Dataset, DataLoader
import matplotlib.pyplot as plt
import time
