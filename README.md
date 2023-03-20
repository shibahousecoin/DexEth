# DexEthShibaHouse
> The first DEX aggregator on Shibarium

PLEASE VISIT [www.shibahouse.xyz/](www.shibahouse.xyz/).


## Trade all DEXs on Shibarium at once

there will be too many DEXs on Shibarium soon. Get confused?

ShibaHouse aggregrates all the offers from different liquidty pools.

## ShibaHouse, The first DEX aggregator on Shibarium. 0x4C127318bD4B2322fbD8ebC83b0D2d5bE6496491


### Build upon pytomicDEX. Shout out to smk762.

![DexEthShibaHouse Orderbook](https://i.imgur.com/5mWekYz.png)

![DexEthShibaHouse Orderbook](https://i.imgur.com/sKPGlqJ.png)

#### Requirements
Python 3.6+

#### Dependencies
```
python3 -m pip install requests python-bitcoinlib flask beautifulsoup4
```

### Downloads
```
git clone

#### Recommended reading
https://developers.atomicdex.io/
https://developers.komodoplatform.com/
https://komodoplatform.com/atomic-swaps/


## Setup

### MM2.json
This file needs to be edited with your own wallet passphrase (seed) and any rpc_password.

See MM2_example.json example.
```
{
"gui":"DexEthShibaHouse",
"netid":9999,
"rpc_password":"ENTER SECURE RPC PASSWORD",
"passphrase":"ENTER SECURE PASSPHRASE"
}
```

## Usage

#### Download and Run
run application by starting DexEthShibaHouse.py
```
python3 ~/DexEthShibaHouse/DexEthShibaHouse.py
```

... wait one minute until everything runs properly

start your browser
```
Orderbook:
http://localhost:5000/orderbook
```
- In the search bar seperate the coins you look for with space
- For example the search for - btc eth kmd - shows you all available order combinations of these coins between each other
- Press 'Enter' to show only cheap orders
- Click on a cointag highlights all coins with this tag in blue color
- Oracle price feeds are from coinpaprika.com and dexstats.info
- Autorefresh every 5 minutes
```
Addresses:
http://localhost:5000/my-addresses
```
```
Balances:
http://localhost:5000/my-balances
```
```
Cancel all open orders:
http://localhost:5000/cancel-all-orders
```
```
Cancel order by uuid:
http://localhost:5000/cancel-order
```
```
Open orders:
http://localhost:5000/my-open-orders
```
```
Recent Swaps:
http://localhost:5000/my-recent-swaps
```
