# ETF Web Application 

![](https://github.com/ScientiaCapital/ETF-Web-Application/blob/main/Images/etef%20pic.jpeg)

In recent years, finance has had an explosion in passive investing. Passive investing means that you invest in a basket of assets that’s called an exchange-traded fund (ETF). This way, you don’t spend time researching individual stocks or companies or take the risk of investing in a single stock. ETFs offer more diversification.

For this Challenge assignment, you need to create and submit the following deliverables:

     - A Jupyter notebook that contains the following:

          - Your analysis of the ETF data that a SQL database stores

          - Professionally styled and formatted interactive visualizations

     - A screenshot or video of the web application that you created by deploying your Jupyter notebook via the Voilà library

Instructions:  Use the etf_analyzer.ipynb notebook to complete your analysis of a fintech ETF that consists of four stocks: GOST, GS, PYPL, and SQ. Each stock has its own table in the etf.db database, which the Starter_Code folder contains.

Analyze the daily returns of the ETF stocks both individually and as a whole. Then deploy the visualizations to a web application by using the Voilà library.


---

## Technologies

Before attempting to execute any _Python_ code in `etf_analyzer.ipynb`, it is imperative that your development environment holds the following modules:

[numpy](https://numpy.org/doc/stable/user/quickstart.html) - Scientific computing module.

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module.

[hvplot](https://hvplot.holoviz.org/getting_started/index.html) - High-level plotting API for PyData ecosystem built on HoloViews

[sqlalchemy](https://www.sqlalchemy.org/) - Relational database module.

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```

import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy

```

## Examples

![Plot](https://github.com/ScientiaCapital/ETF-Web-Application/blob/main/Images/ETF%20Cum%20Returns.png)


## Usage

1. Clone repository onto your personal machine. 

2. Open _Jupyter Lab_ or _Jupyter Notebook_ via _Anaconda Navigator_ and navigate to the directory in which the file `etf_analyzer.ipynb` is present. _All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line_. Ensure that all relevant dependencies and _Python_ modules are installed (see __Technologies__ and __Installation Guide__ for more details) before attempting to execute code within _Jupyter Notebook_; otherwise, you will receive multiple interpreter errors! 

3. With the notebook open, start at the very first cell reading "Import the required libraries and dependencies" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. _It is vital that all cells are ran in sequential order or your notebook will generate compiler errors_!. 

---

## Contributors

New development created by Scientia Capital. **Code from 'Uploaded Starter Files' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship**.

---

## License

Software tool available for public use. 
