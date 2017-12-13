# CS 6220- Team 2- Project Repository

## Instructions for Reproducing Results
The Jupyter notebook and datasets for reproducing the results are contained within the `02_working` folder within the repository. If you want to download the dataset directly (not necessary), you can do that [here](https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7).

The notebook code should be executed in a Python 3 enviroment containing the requirements detailed in `requirements.txt` (within the `02_working` folder). These requirements include standard libraries: `numpy`, `pandas`, `matplotlib`, `scipy`, and `scikit-learn`, in addition to the `plotly` library. 

Several Plotly API credentials are listed in the first Jupyter notebook cell:

```
# Plotly credentials stuff- run first time only
import plotly
plotly.tools.set_credentials_file(username='xalanxlp', api_key='eqGPEiLp525U75zOHDek')
# plotly.tools.set_credentials_file(username='bdesnoy', api_key='VLNSHIH0dfFWjlXNEbiG')
# plotly.tools.set_credentials_file(username='junyi', api_key='sswCNaXW5ssm3JllQCRq')
# plotly.tools.set_credentials_file(username='alankritjoshi', api_key='HeZ3RMcZarDeaMdAeIkU')
# plotly.tools.set_credentials_file(username='RahulKondakrindi', api_key='g2ESjuxlmQieFYPukmJR')
```

If error messages are received that the limits for the specified API key are exceeded, use one of the commented lines to specify a different API key. 
