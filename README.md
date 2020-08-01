# Google_Stock_Price_Estimation

* To use the train dataset, use the following command:
  ```
  train = pd.read_csv('Google_Stock_Price_Train.csv')
  ```
* To run the notebook, you will need to install the following packages:
  ```
  pip install numpy
  pip install pandas
  pip install tensorflow
  pip install keras
  pip install matplotlib
  pip install sklearn
  ```

## Dataset Desciption
  * The dataset describes 6 properties of stocks at different times and is concerned with attributes that indicate the change of stock prices over a specific period of time. 
  * The dataset has the following input categories:
    * RowNumber
    * Date
    * Open
    * High 	
    * Low 	
    * Close 	
    * Volume
  * Input and output attributes are numerical & categorical and there are 1300 instances to work with.
  * Performance for models is evaluated using matplotlib charts. 
