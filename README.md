<div align="center">
  
[1]: https://github.com/Pradnya1208
[2]: https://www.linkedin.com/in/pradnya-patil-b049161ba/
[3]: https://public.tableau.com/app/profile/pradnya.patil3254#!/
[4]: https://twitter.com/Pradnya1208


[![github](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/c292abd3f9cc647a7edc0061193f1523e9c05e1f/icons/git.svg)][1]
[![linkedin](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/9f5c4a255972275ced549ea6e34ef35019166944/icons/iconmonstr-linkedin-5.svg)][2]
[![tableau](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/e257c5d6cf02f13072429935b0828525c601414f/icons/icons8-tableau-software%20(1).svg)][3]
[![twitter](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/c9f9c5dc4e24eff0143b3056708d24650cbccdde/icons/iconmonstr-twitter-5.svg)][4]

</div>

# <div align="center">Web traffic time series forecasting</div>
<div align="center"><img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/intro.gif?raw=true"></div>

## Overview:
Sequential or temporal observations emerge in many key real-world problems, ranging from biological data, financial markets, weather forecasting, to audio and video processing. The field of time series encapsulates many different problems, ranging from analysis and inference to classification and forecast.

This project focuses on the problem of forecasting the future values of multiple time series, as it has always been one of the most challenging problems in the field.
Here, we specifically focused on the problem of forecasting future web traffic for approximately 145,000 Wikipedia articles.
## Dataset:
The training dataset consists of approximately 145k time series. Each of these time series represent a number of daily views of a different Wikipedia article, starting from July, 1st, 2015 up until December 31st, 2016.
For each time series, you are provided the name of the article as well as the type of traffic that this time series represent (all, mobile, desktop, spider).
### File description:
Files used for the first stage will end in '_1'. Files used for the second stage will end in '_2'. Both will have identical formats. The complete training data for the second stage will be made available prior to the second stage.

- train_*.csv - contains traffic data. This a csv file where each row corresponds to a particular article and each column correspond to a particular date. Some entries are missing data. The page names contain the Wikipedia project (e.g. en.wikipedia.org), type of access (e.g. desktop) and type of agent (e.g. spider). In other words, each article name has the following format: 'name_project_access_agent' (e.g. 'AKB48_zh.wikipedia.org_all-access_spider').
- key_*.csv - gives the mapping between the page names and the shortened Id column used for prediction
## Implementation:

**Libraries:**  `NumPy`   `pandas` `sklearn`  `Matplotlib`

## Data exploration:
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/eda1.PNG?raw=true">
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/eda2.PNG?raw=true">

## Forecast Methods:
### SMAPE, the measurement:
The SMAPE is one of the alternatives to overcome the limitations with MAPE forecast error measurement. In contrast to the mean absolute percentage error, SMAPE has both a lower bound and an upper bound, therefore, it is known as symmetric. The ‘S’ in SMAPE stands for symmetric, ‘M’ stands for mean which takes in the average value over a series, ‘A’ stands for absolute that uses absolute values to keep the positive and negative errors from canceling one another out, ‘P’ is the percentage which makes this accuracy metric a relative metric, and the ‘E’ stands for error since this metric helps to determine the amount of error our forecast has.
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/smape.PNG?raw=true" width="50%">

<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/smape_plot.PNG?raw=true">

### Simple median model:
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/simple%20median.PNG?raw=true" width="60%">

### Median model - weekday, weekend and holiday:
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/median2.PNG?raw=true" width="60%">

### ARIMA model:
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/arima.PNG?raw=true" width="60%">

### Facebook prophet library:
Facebook prophet library is created by facebook and aims to create a human-friendly time series forecasting libary.
<img src="https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/output/log.PNG?raw=true" width="60%">

Checkout the [Notebook](https://github.com/Pradnya1208/Web-Traffic-Time-Series-Forecasting/blob/main/web_traffic_time_series_forecasting.ipynb) for complete analysis.
### Learnings:
`Time Series Forecasting`






## References:
[SMAPE](https://www.kaggle.com/cpmpml/smape-weirdness)<br>
[Facebook prophet](https://facebookincubator.github.io/prophet/)


### Feedback

If you have any feedback, please reach out at pradnyapatil671@gmail.com


### 🚀 About Me
#### Hi, I'm Pradnya! 👋
I am an AI Enthusiast and  Data science & ML practitioner



[1]: https://github.com/Pradnya1208
[2]: https://www.linkedin.com/in/pradnya-patil-b049161ba/
[3]: https://public.tableau.com/app/profile/pradnya.patil3254#!/
[4]: https://twitter.com/Pradnya1208


[![github](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/c292abd3f9cc647a7edc0061193f1523e9c05e1f/icons/git.svg)][1]
[![linkedin](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/9f5c4a255972275ced549ea6e34ef35019166944/icons/iconmonstr-linkedin-5.svg)][2]
[![tableau](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/e257c5d6cf02f13072429935b0828525c601414f/icons/icons8-tableau-software%20(1).svg)][3]
[![twitter](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/c9f9c5dc4e24eff0143b3056708d24650cbccdde/icons/iconmonstr-twitter-5.svg)][4]

