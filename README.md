# Stock Prediction using LSTM

Stock Prediction is volatile. Do not use this as your primary model of prediction, no matter how sweet the output might
be. 

File info: 
1. stock-info.ipynb
2. stock-lstm.ipynb

stock-info.ipynb: Contains data visualizations for the index predicted. Please be careful in inputting the correct index. 
Data source must be either Kaggle or Alphavantage. Handling other data sources will be implemented during revision. 

stock-lstm.ipynb: Contains the actual code including model implementation, error of the model and quantitatively comparing
Simple and Stacked LSTM networks. 

To run the codes: cd into your desired directory and clone the repository. 
> git clone https://github.com/akshathmangudi/Stock-Prediction.git

Install the necessary dependencies. 
1. tensorflow
2. numpy
3. pandas
4. matplotlib
5. pandas-datareader
6. scikit-learn
7. keras

> pip install tensorflow
> pip install numpy
> pip install pandas
> pip install matplotlib
> pip install pandas-datareader
> pip install scikit-learn
> pip install keras

Or, this can be used: 
> pip install -r dependencies.txt

Step 2: dir into the repo and run the code you want to run. 
For stock-info: 
> jupyter notebook stock-info.ipynb

For stock-lstm: 
> jupyter notebook stock-lstm.ipynb

If you encounter any errors, please contact me on Gmail and specify the error. 
Email: akshathmangudi@gmail.com
