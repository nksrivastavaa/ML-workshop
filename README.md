# ML-workshop

This repostory contains the notebooks used in the Hands-on Workshop on Python Libraries for Machine Learning

The notebook names are self descriptive and can be run directly by opening them and clicking on "Open in Colab" 

You can find our slides [here](https://www.canva.com/design/DAFYdcGfOwk/w8OjCQPACr1V-mdw2xP1Qg/view?utm_content=DAFYdcGfOwk&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

This repo also contains the "weatherAUS.csv" dataset which we will use to learn how to handle Classification problems using Machine Learning. 

*[Dataset Source: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package]*

### **How to download this dataset?**

1) First import pandas: <br>
`import pandas as pd`

2) Download the dataset from this repo using the command: <br>
`!wget https://raw.githubusercontent.com/nksrivastavaa/ML-workshop-dataset/main/weatherAUS.csv`

3) Load the dataset into a pandas dataframe: <br>
`raw_df = pd.read_csv('weatherAUS.csv')`

4) You can get info on the dataset by: <br>
`raw_df.info()`


