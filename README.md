# FinanssiCoins

## Description
Finanssi-Coin is a cryptocurrency price tracker which gets the 20 most popular cryptocurrencies from the [Coin Gecko API](https://www.coingecko.com/en/api) and displays them in a list with charts using React Native.

## Set up
1. `https://github.com/JAY9039/Finanssi-Coins.git` 
2. `cd FinanssiCoin`
3. `npm install`
4. `expo start`
5. Scan the QR code on screen to run it on your device, or write `i` or `a` in your expo terminal to open it in either iOS or Android

## Api Setup

1. `URL: https://www.coingecko.com/en/api/documentation?` 
2. `Goto Coins Section --> /coins/market`
Use this to obtain all the coins market data (price, market cap, volume)
3. You can setup your GET request for this 
      1. vs_currency
      2. per_page
      3. price_change_percentage
4. Click on Execute Button.
5. Get the executed Request URL. 
(This List all coins with market data)

!!! info
NOTE: You can change in values according to your needs.