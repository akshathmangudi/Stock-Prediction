# Stock Prediction
NOTE: STOCK PREDICTION IS VOLATILE. DO NOT USE THIS AS YOUR PREDICTION MODEL.

File info: 
1. stock-info.ipynb
2. stock-lstm.ipynb

stock-info.ipynb: Contains data visualizations for the index predicted. Please be careful in inputting the correct index. 
Data source must be either Kaggle or Alphavantage. Handling other data sources will be implemented during revision. 

stock-lstm.ipynb: Contains the actual code including model implementation, error of the model and quantitatively comparing
Simple and Stacked LSTM networks. 

Clone the repository:
```bash
$ git clone https://github.com/akshathmangudi/Stock-Prediction.git
$ Stock-Prediction/
```

## Table of Contents
<a href=""> Creating a virtualvenv </a>
<a href=""> Dependencies </a>
<a href=""> Run the notebook </a>

### Creating virtualvenv
For Python 3.6+ users: 
```shell
$ python -m venv /path/to/virtualenv
```
For activation of virtualenv:
bash/zsh: 
```bash 
$ source <venv>/bin/activate
```
fish: 
```shell
$ source <venv/bin/activate.fish
```
cmd.exe: 
```shell
C:\> <venv>\Scripts\activate.bat
```
```shell
PowerShell: 
PS C:\> <venv>\Scripts\activate.ps1
```

For conda users, the following commands are to be sequentially passed into your terminal:
```bash
$ conda -V
$ conda update conda
$ conda create -n <envname> python=x.x anaconda
$ conda activate <envname>
```

For deactivation: 
```bash
$ conda deactivate
```

### Dependencies
The dependencies required to run this notebook can be installed using the below command. 
```bash
$ pip install -r requirements.txt
```

### Run the notebook
For stock-info:
```bash
jupyter notebook stock-info.ipynb
```

For stock-lstm:
```bash
jupyter notebook stock-lstm.ipynb
```

Project by Akshath Mangudi (2023)