# Trading-Bot

## An AI-driven trading bot leveraging sentiment analysis with deep learning to automate stock trading decisions, integrating Alpaca's API for real-time market data, backtesting using Yahoo Finance data, and SQL for storing earnings and performance metrics.


This project showcases an AI-powered trading bot designed to automate stock trading decisions using machine learning and natural language processing (NLP). The bot leverages sentiment analysis of financial news headlines to guide its decisions and is built with Python, incorporating several advanced libraries and tools. For sentiment analysis, it uses the FinBERT model from Hugging Face’s Transformers library, fine-tuned for financial sentiment classification. Deep learning models run efficiently with the PyTorch framework, utilizing GPU acceleration when available. The bot connects to Alpaca's API to access real-time market data and execute trades in a paper trading environment, secured through API key authentication. Backtesting capabilities are implemented using Yahoo Finance data via the YahooDataBacktesting module. Additionally, the bot employs an SQL database to store earnings and performance metrics, streamlining data management and analysis. This project seamlessly integrates NLP and financial data processing to deliver a sophisticated trading system capable of making autonomous, data-driven trading decisions.

<img width="1422" alt="Screenshot 2024-07-16 at 3 59 45 PM" src="https://github.com/user-attachments/assets/0cd49663-c8a9-46cc-be77-6e5e0080e504">


<img width="1004" alt="Screenshot 2024-07-16 at 4 05 06 PM" src="https://github.com/user-attachments/assets/179ee0d5-07ca-4018-ab27-7d5f711f7a56">

## How to Run the Bot
1. Create a virtual environment `conda create -n trader python=3.10` 
2. Initialize it `conda init zsh`
3. Activate it `conda activate trader`
4. Install initial dependencies `pip install lumibot timedelta alpaca-trade-api==3.1.1`
5. Install libraries `pip install torch torchvision torchaudio transformers` 
6. Update the `API_KEY` and `API_SECRET` with values from your Alpaca account 
7. Run the bot `python3 tradingbot.py`

