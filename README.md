# WRSI Backtesting Strategy

This project implements a backtesting strategy using the Wilder's Relative Strength Index (WRSI) on Ethereum (ETH) price data. It aims to identify optimal parameters for buy and sell signals based on WRSI to maximize returns.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have Python installed on your system. This project is built with Python 3.8 or later.

### Setting Up a Virtual Environment

To avoid conflicts with other projects or your global Python installation, it's recommended to use a virtual environment. Here's how to set it up:

1. **Create a Virtual Environment:**

   Navigate to your project's directory in the terminal and run:

   ```bash
   python -m venv venv
   ```

   This command creates a virtual environment named `venv` in your project directory.

2. **Activate the Virtual Environment:**

   - On Windows, activate the virtual environment by running:

     ```bash
     .\venv\Scripts\activate
     ```

   - On macOS and Linux, use:

     ```bash
     source venv/bin/activate
     ```

   Your command line will now show the name of the activated virtual environment, indicating that any Python or pip commands will operate within this isolated environment.

### Installing Dependencies

With the virtual environment activated, install the project dependencies by running:

```bash
pip install -r requirements.txt
```

This command reads the `requirements.txt` file and installs all the necessary Python packages. For this project, your `requirements.txt` should include:

```
numpy
pandas
matplotlib
yfinance
```

### Running the Project

With the dependencies installed, you can run the project's main notebook script:

```bash
python main.py
```

Replace `main.py` with the name of your Python script containing the backtesting strategy.

## Strategy Overview

The project uses WRSI to generate buy and sell signals for ETH-USD based on predefined thresholds. Then you can iterates through a range of parameters to find the combination that results in the best performance over the specified backtest period.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

