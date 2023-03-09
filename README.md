# Module19_Assignment - Fintech Finder 

Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them
As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

# Technologies and Librabries Used 
***Python***
- import os
- import requests
- from dotenv import load_dotenv
- load_dotenv()
- from bip44 import Wallet
- from web3 import Account
- from web3 import middleware
- from web3.gas_strategies.time_based import medium_gas_price_strategy
- import streamlit as st
- from dataclasses import dataclass
- from typing import Any, List
- from web3 import Web3
- w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

https://streamlit.io/

https://web3py.readthedocs.io/en/stable/overview.html

https://pypi.org/project/bip44/

https://trufflesuite.com/docs/ganache/

# Usage 

In the terminal navigate to fintech_finder app.py  and run streamlit app, Selected candidate "Jo" and hired for 1 hour and click  send transaction, hash code validated.

![confirmation](https://github.com/mbhat83/Module19_Assignment/blob/main/Screenshots/confirmation.PNG)

Naviagte to Ganache app check the balance on the Ethereum account. 

![Balance](https://github.com/mbhat83/Module19_Assignment/blob/main/Screenshots/Balance.PNG)

Navigate to Transaction section of Ganache and confirmed the transaction 

![transaction](https://github.com/mbhat83/Module19_Assignment/blob/main/Screenshots/transaction.PNG)


Contributors
Madhuri 



 
