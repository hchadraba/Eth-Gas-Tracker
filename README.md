# Ethereum Gas Tracker

Simple Python script that monitors Ethereum gas prices using the Etherscan API.

This tool prints Safe / Propose / Fast gas price tiers and can be used to watch for cheaper transaction timing.

Features

- Pulls live Ethereum gas price data from Etherscan
- Displays Safe / Propose / Fast gas tiers
- Runs continuously with adjustable refresh interval
- Alerts when gas drops below a selected threshold

Setup

Install dependencies:

pip install -r requirements.txt

Set your Etherscan API key:

export ETHERSCAN_API_KEY=your_api_key_here

Run the script:

python eth_gas_tracker.py
