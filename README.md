# Portfolio Risk-Return Analysis

This analysis evaluates four portfolios for inclusion in our client's portfolios:

* SOROS FUND MANAGEMENT LLC
* PAULSON & CO.INC.
* TIGER GLOBAL MANAGEMENT LLC
* BERKSHIRE HATHAWAY INC.

Various calculations for risk management are completed including: daily returns, standard deviations, variances, covariances, Sharpe ratios, and betas. Additionally the funds are visualized against eachother and the S&P 500 through rolling SMAs and betas.

![Rolling_21_Day_Standard_Deviation](https://github.com/rrmangum/Portfolio_Risk_Return_Analysis/blob/main/Images/Rolling_21_Day_Standard_Deviation.png?raw=true)

Ultimately I reccomend Tiger Global Management LLC as the main fund to be included in our client portfolios. While, Berkshire Hathaway INC returns greater profits, the risk associated with those returns is much higher than the risk level from Tiger Global Management LLC.

---

## Technologies

This analysis uses python Python 3.9.12 and the following libraries:
* [Pandas](https://pandas.pydata.org/) - Provides the calculating functions, and data manipulation necessary to conduct this analysis.
* [Pathlib](https://docs.python.org/3/library/pathlib.html) - Provides the path to a CSV database.
* [NumPy](https://numpy.org/doc/stable/user/index.html#user) - Provides the square root function.

---

## Installation Guide

Download [Anaconda](https://www.anaconda.com/products/distribution) to your computer. In your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:

```python
jupyter lab
```

---

## Usage

This analysis is not meant as financial advice, and is purely a comparison of major portfolios against the S&P 500 for risk management purposes.

## Contributors

Ryan Mangum - [LinkedIn](https://www.linkedin.com/in/ryanrmangum/) | rrmangum@gmail.com

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) [2022] [Ryan Mangum]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

