# Forecasting-Net-Prophet

Time series analysis using Facebook Prophet.

---

## Technologies

This project leverages python 3.9 with the following package:

* [Pandas](https://pandas.pydata.org/) - Entry point, open source data analysis and manipulation tool.

* [Facebook Prophet](https://facebook.github.io/prophet/) - Time series forecasting that Facebook developed to analyze their data.

* [hvPlot](https://hvplot.holoviz.org/) - Provides an alternative for the static plotting API provided by Pandas and other libraries.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews
```

Next, import required libraries and dependencies.

```python
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
import numpy as np
%matplotlib inline
```

---

## Usage

To use this application simply clone the repository and run the **forecasting_net_prophet.ipynb** with:

```python
  forecasting_net_prophet.ipynb
```

---

## Contributors

This project brought to you by Agnes.

---

## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)
