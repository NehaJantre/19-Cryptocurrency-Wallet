# FinTech-Module-19-Challeng: Cryptocurrency Wallet


## Application:
In this Challenge, you will assume the perspective of a Fintech Finder
customer in order to do the following:

* Generate a new Ethereum account instance by using your mnemonic seed phrase
 (which you created earlier in the module).

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Kovan testnet.

* Review the transaction hash code associated with the validated blockchain transaction.

 Once you receive the transaction’s hash code, you will navigate to [Kovan’s Etherscan](https://kovan.etherscan.io/) website to review the blockchain
transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.


---
## Technologies

In this challenge, you’ll use the following libraries:

* [pandas](https://pandas.pydata.org/docs/) 

* [Streamlit](https://streamlit.io/) 

* [Data Classes](https://docs.python.org/3/library/dataclasses.html) 
* [datetime](https://docs.python.org/3/library/datetime.html)

* [typing](https://docs.python.org/3/library/typing.html)

* [hashlib](https://docs.python.org/3/library/hashlib.html)
* [Web3.py](https://web3py.readthedocs.io/en/stable/overview.html): A Python library for connecting to and performing operations on Ethereum-based blockchains.

* [ethereum-tester](https://pypi.org/project/ethereum-tester/0.1.0a4/): A Python library that provides access to the tools we’ll use to test Ethereum-based applications.

* [mnemonic](https://pypi.org/project/mnemonic/): A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

* [bip44](https://pypi.org/project/bip44/): A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

* Infura API: An API that provides instant access to the Ethereum network over HTTPS (i.e., the web). You will need to create an account with Infura.

---
## Installation Guide:
### To install the Streamlit library, check that your dev virtual environment is active, and then run the following command:
```
pip install streamlit
```
### To install the Web3.py library, check that your dev environment is active, and then run the following:
```
pip install web3==5.17
```
### To install the ethereum-tester library, check that your dev environment is active, and then run the following:
```
pip install eth-tester==0.5.0b3
```
### To install the mnemonic package, check that your dev environment is active, and then run the following:
```
pip install mnemonic
```
### To install the bip44 package, check that your dev environment is active, and then run the following:
```
pip install bip44
```
### Open an Account with Infura API: To create an Infura account, navigate to the Infura website’s [registration page](https://infura.io/dashboard), then register for an account.
---

## Examples
### Gitbash command
![address balance](/Images/gitbash.png))

### Transaction
![address balance](/Images/sidebar.png))
### Sender Account history
![address balance](/Images/senderaccount.png))
### Sender transaction
![address balance](/Images/transaction.png))
### Fintech Finder candidate account
![address balance](/Images/recepient.png))

---
## Contributors

Brought to you by Neha Jantre.

---

## License

MIT
