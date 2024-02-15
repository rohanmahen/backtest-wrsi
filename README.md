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

## Contributing

Contributions to improve the notebook or explore new strategies are welcome. Please fork the repository and submit pull requests with your enhancements.

## License

This project is licensed under the MIT License. See the LICENSE file in the repository for more information.
