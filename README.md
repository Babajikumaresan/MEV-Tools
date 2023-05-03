# MEV-Tools

[^1] This is a sample code, tested in mainnet

>Author Babaji kumaresan

[^2] Use it for educational purpose only

[^3] you have to set the time out before selling the token else it will give error

[^4] i have added eth_to_pepe_rate fixed quantity, change it dynamic to improve the code


**How to install**

Use Pycharm for desktop.

Install required imports
>requirments file updated in the repo
```
pip install -r requirements.txt 
```
**Address :**
weth_address = "0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2"

uniswap_v3_router_address = "0xE592427A0AEce92De3Edee1F18E0157C05861564"

pepe_eth_pair_address = "0x11950d141ecb863f01007add7d1a342041227b58"

Verify it in Ethscan,do this is correct address. pepe_eth_pair_address this is pep vs ETh token pool address. 
when you are running code, if this address dont have any token. you have to rewatch the pool again in coinmarketcap.

```ruby
Example :

https://coinmarketcap.com/dexscan/ethereum/0x88e6a0c2ddd26feeb64f039a2c41296fcb3f5640/

This is the WTH/USDC
Select the glass near to pair. it will take you to https://etherscan.io/address/0x88e6a0c2ddd26feeb64f039a2c41296fcb3f5640

This is the address for WETH/USDC Pool 0x88e6a0c2ddd26feeb64f039a2c41296fcb3f5640

Pool is where you send your USDC to get WETH or sending WETH to get USDC.

```

(when the code is written, pepe is the trending token in ETh chian, its not the recommendation to buy)
(Any token literally can go to zeroo)

 
 A   Mempool-->Monitor Trades;
 B   Monitor Trades-->Place Buy(D);
 

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
then add the required private key and infura api key

then you are good to go :)

Thank me later.
