# awesome-TS-predict
A curated list of awesome time series predict algorithm, libraries and software.

~~Read~~ this in [English](./README.md), [Traditional Chinese](./README-ZH-TW.md)~~


## Contents

* [Research Summaries and Trends](#research-summaries-and-trends)
* [Research Labs](#research-labs)
* [Tutorials](#tutorials)
  * [Reading Content](#reading-content)
  * [Videos and Courses](#videos-and-online-courses)
  * [Books](#books)
* [Libraries](#libraries)
  * [Deep Learning Methond](#deep-learning-methond)
  * [Statistical Method](#statistical-method)
* [Datasets](#datasets)
* [Credits](#credits)

## Research Summaries and Trends




## Research Labs
[Back to Top](#contents)

* [Tensorflow](https://www.tensorflow.org/tutorials/structured_data/time_series) - This tutorial is an introduction to time series forecasting using TensorFlow. It builds a few different styles of models including Convolutional and Recurrent Neural Networks (CNNs and RNNs).
* 



## Tutorials
[Back to Top](#contents)

### Reading Content

Paper

* [DeepAR](https://arxiv.org/abs/1704.04110)
* [MQCNN\RNN](https://arxiv.org/abs/1711.11053)
* [Fbprophet](https://peerj.com/preprints/3190/)




Blog

* [Karpathy's The Unreasonable Effectiveness of Recurrent Neural Networks](https://karpathy.github.io/2015/05/21/rnn-effectiveness)
* [colah's blog: Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* [Jason Brownlee: What Is Time Series Forecasting?](https://machinelearningmastery.com/time-series-forecasting/)


### Videos and Online Courses
[Back to Top](#contents)



### Books

* [Practical Time Series Analysis](https://web.stanford.edu/~jurafsky/slp3/)
* [Introduction to Time Series Forecasting With Python](https://machinelearningmastery.com/introduction-to-time-series-forecasting-with-python/)


## Libraries

[Back to Top](#contents)

### Deep Learning Methond

  * [LSTM](https://github.com/jaungiers/LSTM-Neural-Network-for-Time-Series-Prediction) - LSTM built using the Keras Python package to predict time series steps and sequences. Includes sine wave and stock market data.
  * [Seq2Seq](https://github.com/JEddy92/TimeSeries_Seq2Seq) - This repo aims to be a useful collection of notebooks/code for understanding and implementing seq2seq neural networks for time series forecasting. Networks are constructed with keras/tensorflow.
  * [DeepAR](https://github.com/arrigonialberto86/deepar) - Seq2Seq model for probabilistic time series.
  * [GluonTS](https://github.com/awslabs/gluon-ts) - GluonTS is a Python toolkit for probabilistic time series modeling.GluonTS provides utilities for loading and iterating over time series datasets, state of the art models ready to be trained, and building blocks to define your own models and quickly experiment with different solutions.





### Statistical Method

  * [Fbprophet](https://facebook.github.io/prophet/) - Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
  * [scikit-learn](https://scikit-learn.org/stable/) - Simple and efficient tools for predictive data analysis
  * [Sklearn for pandas](https://github.com/scikit-learn-contrib/sklearn-pandas) - This module provides a bridge between Scikit-Learn's machine learning methods and pandas-style Data Frames. In particular, it provides a way to map DataFrame columns to transformations, which are later recombined into features.
  * [Statsmodels](https://www.statsmodels.org/stable/index.html) - statsmodels is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration.

  


## Datasets

[Back to Top](#contents)

- [COVID-19 time series](https://github.com/datasets/covid-19) - Coronavirus disease 2019 (COVID-19) time series listing confirmed cases, reported deaths and reported recoveries. Data is disaggregated by country (and sometimes subregion). 
- [Numenta's NAB](https://github.com/numenta/NAB) - NAB is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications. It is comprised of over 50 labeled real-world and artificial timeseries data files plus a novel scoring mechanism designed for real-time applications.
- [Yahoo's Webscope S5](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70) - The dataset consists of real and synthetic time-series with tagged anomaly points. The dataset tests the detection accuracy of various anomaly-types including outliers and change-points.


## License
[License](./LICENSE) - CC0
