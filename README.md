# Duino-Pay
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Deenpro1/Duino-Pay/graphs/commit-sctivity) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
### Duino Pay - Duinocoins stable fork made for payments

## What is Duino Pay?
Duino Pay is a separate chain (soft fork) of duino coin with no mining. It is centralised and has a minting through burning system with a 1:1 value to the Yen ¥. 

## Why should you pay in Duino Pay?
The value of Duino Coin isn't stable, so making a transaction can result in a different amount from creating it until recieval. 
Duino Pay is a stablecoin, which makes transactions more secure to price drops. 

## How do I get my DUCO into DPAY?
To mint DPAY, you will need to visit our minting site. There, you enter your DPAY username and will be assigned a UUID which you put into the memo of the minting transaction.
Then, you send your DUCO to coinburn with the memo. The app will search for any transaction going to coinburn with the specific UUID. If a transaction gets sent and verified by a node,
the data (username, username DPAY, date, time, amount, txid, verified:, success:) into a MySQL database

## How do I get DPAY into DUCO?
Because to mint DPAY the duco goes to coinburn, there is no supply in DUCO to trade with up to now. I will be thinking about how to solve this because I don't want to profit.

## Development:
### Frontend HTML site
### Transaction scanner
### Secondary Blockchain
### Wallet

## Hosting:
When we leave the alpha, I will rent a CX23 from hetzner

## Goals:
- [ ] Finish the Website
- [ ] Blockchain and Wallet implementation 
- [ ] SSL certificate for the Api and Website
- [ ] Go Live!
