## Day-ahead Forecasts of Air Temperature

With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript:

> H. Wang, M. S. Pathan, Y. H. Lee, and S. Dev, Day-ahead Forecasts of Air Temperature, Proc. IEEE AP-S Symposium on Antennas and Propagation and USNC-URSI Radio Science Meeting, 2021.


### Executive summary
Climate change is a phenomenon that can affect many departments including health, development, and planning. In this reseach, we proposed a robust time sequence model using triple exponential smoothing method to predict ground-based air temperature values using historical values. Our model quantitively achieved improvement in capturing the seasonal variability of temperature and conducted quantitative evaluation on RMSE values.



### Code
All codes are written in `python3`.
+ `forecasting-example1.py`: Computes the forecasting performance and plots the result for sample example 1.
+ `forecasting-example2.py`: Computes the forecasting performance and plots the result for sample example 2.
+ `benchmarking.py`: Computes the performance of our proposed method, along with other benchmarking methods. 


### Results
The results are stored in the folder `./results/`.
+ `prediction-index146.PDF`: Plot of forecasting example 1.
+ `prediction-index20.PDF`: Plot of forecasting example 2.
+ `comparison.txt`: Text file that details the performance of the various benchmarking methods.


### Datasets
The dataset used in our case study can be found in the folder `./data/`.
