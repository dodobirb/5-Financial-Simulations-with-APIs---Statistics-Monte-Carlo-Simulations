# 5: Financial Simulations with APIs - Statistics & Monte Carlo Simulations
FinTech Boot Camp Module 5 Challenge

---

EK FinTech Consulting, LLC developed this prototype program for Credit Union X for client financial health evaluations. The two primary purposes of this program are to enable clients to:

* Assess their monthly budgets
* Forecast a reasonably effective retirement plan based on their current combined holdings of cryptocurrencies, stocks, and bonds

The *Usage* section describes the specific tools with which to carry out these objectives.

---

## Installation Guide

Ensure through your local terminal that your development environment supports the following imports and dependencies:

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```

If it does not, reference your terminal installation guide to download the missing software.

---

## Usage

Tools for 

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.

---

## Contributors

Brought to you by EK FinTech Consulting developer Erin Kenny.

ekenny3@uncc.edu

www.linkedin.com/in/e-kenny

---

## License

MIT

License file included in repository.


