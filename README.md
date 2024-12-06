# Deep Learning-based Recommendation System Using NCF(Neural-Collaborative-Filtering)
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

## Show Train Result and Recommend items
- Result Table
<img src="https://github.com/user-attachments/assets/446cb79f-1752-47c8-8762-11840123f5f7" alt="image" width="400"/>


- Recommend Items
<img src="https://github.com/user-attachments/assets/9e7dbcd4-22bc-4b08-8c4a-f06453eb1f8c" alt="image" width="100"/>
<img src="https://github.com/user-attachments/assets/f3ffb937-eafd-4e2c-90f1-8a9a0ac7bf2b" alt="image" width="100"/>
<img src="https://github.com/user-attachments/assets/b54207de-722e-45dd-b54f-5306fd47c433" alt="image" width="100"/>
<img src="https://github.com/user-attachments/assets/d37853b7-23a0-4f27-ab9c-1c9d95b9e53b" alt="image" width="100"/>

- etc..
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
import time'''

