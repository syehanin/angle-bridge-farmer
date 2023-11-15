# Angle-bridge-farmer
This script swap ~0.0004 BNB (random values) to agEUR using Pancakeswap in BSC network and than bridge it to Celo and Gnosis chains via Layerzero bridge.

## Prerequisites

- Top up your account with BNB in BSC network
- Add private keys to private_key.txt (one line - one key)
- You might change min/max delay between accounts and amount to bridge in BNB in config.py

## Installation

Run commands like this:

```
apt install python3-pip, git
git clone https://github.com/Kizliak/angle-bridge-farmer
cd angle-bridge-farmer
pip install -r requirements.txt
```

Add private keys:

```
nano private_key.txt
```

Run script
```
python3 main.py
```
#1
