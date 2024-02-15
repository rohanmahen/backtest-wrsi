# WRSI Backtesting Strategy Notebook

This Jupyter notebook implements a backtesting strategy using Wilder's Relative Strength Index (WRSI) on Ethereum (ETH) price data. It explores optimal buy and sell signal parameters to maximize trading strategy returns.

## Getting Started

Follow these instructions to get the notebook up and running on your local machine for development, testing, or exploration purposes.

### Prerequisites

- Python 3.8 or later
- Jupyter Notebook or JupyterLab installed in your Python environment
- Basic familiarity with Python and Jupyter notebooks

### Setting Up a Virtual Environment

Creating a virtual environment is recommended to manage dependencies without affecting your global Python setup.

1. **Navigate to your project directory** and create a virtual environment:

   ```bash
   python -m venv venv
   ```

2. **Activate the virtual environment:**

   - Windows:

     ```bash
     .\venv\Scripts\activate
     ```

   - macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

### Installing Dependencies

With the virtual environment activated, install the necessary dependencies:

```bash
pip install -r requirements.txt
```

Your `requirements.txt` should include the necessary libraries, such as:

```
numpy
pandas
matplotlib
yfinance
jupyterlab
```

### Running the Notebook

With dependencies installed, launch JupyterLab or Jupyter Notebook:

```bash
jupyter lab
```

Or for Jupyter Notebook:

```bash
jupyter notebook
```

Navigate through the Jupyter interface to open `backtest.ipynb`. You can now interact with the notebook, running cells to execute the backtest strategy.

## Notebook Overview

`backtest.ipynb` contains Python code and markdown cells that guide you through the process of fetching Ethereum price data, calculating WRSI, and evaluating trading signals for profitability. Then you can it iterates over the key parameters to identify the most strategy outperformance vs buy-and-hold.

## License

This project is licensed under the MIT License. See the LICENSE file in the repository for more information.

## Disclaimer!

This notebook and its contents are for informational and educational purposes only and should not be construed as financial advice. The strategies and analyses discussed in this notebook are not recommendations to buy, sell, or hold any securities or digital assets. The authors and contributors of this notebook are not responsible for any losses, damages, or other consequences that may result from applying the strategies or using the information provided. Users should conduct their own research and consult with a professional financial advisor before making investment decisions. The market data used in this notebook is believed to be from reliable sources, but its accuracy and completeness cannot be guaranteed.

By using this notebook, you acknowledge and agree to this disclaimer and assume full responsibility for any and all of your actions.
