# crypto_wallet_fintech_finder
Challenge 19
Hire a fintech professional and make a payment using cryptocurrency.

## Requirements
This program uses the following libraries:
- Streamlit
- Dotenv
- bip44
- web3

To run this program, perform the following steps:
1. Clone the github repository
```shell
git clone https://github.com/avangelinac/crypto_wallet_fintech_finder.git
```
2. Change to the new directory:
```shell
cd 19_Fintech_Finder
```
3. Install the required packages in a conda environment (replace "myenv" with an environment name of your choice):
```shell
conda create -n myenv python=3.7
```
4. Install the required packages:
```shell
pip install -r requirements.txt
```
5. Run the program:
```shell
streamlit run fintech_finder.py
```

## Usage
To run this program, you must create an Infura project on the Kovan Ethereum testnet. Click [here](https://infura.io/) to create a project, then copy the project ID and mnemonic to a .env file with the following format:

```
MNEMONIC='xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx'
WEB3_INFURA_PROJECT_ID='xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
```

## Example
![Example](Images/screenshot.png)

## Contributors
AC & Opensource