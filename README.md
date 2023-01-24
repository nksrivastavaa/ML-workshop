# ML-workshop-dataset
This repo contains the weatherAUS.csv dataset

How to download this dataset?

1) First import pandas:
import pandas as pd

2) Download the dataset from this repo using the command:
!wget https://raw.githubusercontent.com/nksrivastavaa/ML-workshop-dataset/main/weatherAUS.csv

3) Load the dataset into a pandas dataframe:
raw_df = pd.read_csv('weatherAUS.csv')

4) You can get info on the dataset by:
raw_df.info()
