## AIO Wallet Features

- Embedded Chromium Browser.
- Multiple online wallets.
- List Of Faucets.
- Asset Explorer.
- Salted Password Manager.
- Network Observers
- Fastest Wallet Selection
- Add Mining and Plotting features
- Block Explorer
- Password Manager
***NOTE: the password manager works by encrypting your passphrase with AES Encryption that's generated from a code that the user can specify. if the user loses this code it will be pretty much impossible to recover your account passphrase.

###Uses Api Calls to each wallet. times the time it takes for each call and determines which is on the highest block to make its decision on the best wallet for that user at that specific time. added bonus to this is it self load balances.

## Install

1) Download the Zip
2) Extract contents to a folder
3) To quick start just open BurstAIOWallet.exe in the root folder
4) The block chain will need to sync before you can use the Local Wallet! 
5) by default the fastest Online Wallet will be loaded

## Fast Block-Chain Sync
1) For faster blockchain sync you can downlaod most of it here https://www.dropbox.com/s/xh3p3i8o9idlt5x/burst_db.zip?dl=0
2) Extra files from burst_db.zip to burst_db folder in the wallet, then open BurstAIOWallet.exe
***Note: if burst_db folder doesnt exist in the root simply create one

## Running only a Node
1) to start a local node open the conf folder and edit the nxt properties file:
X.X.X.X is your host ip the node will be runing from
nxt.myAddress=X.X.X.X
nxt.allowedBotHosts=127.0.0.1; localhost; X.X.X.X; 0:0:0:0:0:0:0:1;
nxt.allowedUserHosts=127.0.0.1; localhost; X.X.X.X; 0:0:0:0:0:0:0:1;
2) if you want to set up an online wallet add *; to allowedBotHosts and allowedUserHosts fields
3) if you just want to run a node and not the .exe just use the run.bat(Windows) or run.sh(Linux)

# Burstcoin

The world's first HDD-mined cryptocurrency using the new algorithm, Proof-of-Capacity.

## Burst Features

- Proof of Capacity - ASIC Proof / Energy efficient mining
- Fast sync. with multithread CPU or OpenCL/GPU (optional)
- "Turing complete" smart contracts, via Automated Transactions (AT) https://ciyam.org/at/at.html
- Decentralized Crowdfunding and Lottery via AT
- Asset Exchange and Digital Goods Store
- Advanced transactions: Escrow and Subscription
- Encrypted Messaging

## Burst Specification

- NXT based
- Proof of Stake Removed
- Proof of Capacity implemented
- No IPO
- No Premine
- 4 minute block time
- 2,158,812,800 coins total
- Block reward starts at 10,000/block
- Block Reward Decreases at 5% each month

## Burst Version History

- 2017/02/21 New version relaase Burst 1.2.8
- 2016/16/11 New version release Burst 1.2.7
- 2016/27/07 New version release Burst 1.2.6
- 2016/19/07 New version release Burst 1.2.5
- 2016/06/07 New version release Burst 1.2.4            
- 2016/01/11 Community takeover
- 2015/04/20 New version release Burst 1.2.3
- 2015/02/05 New version release Burst 1.2.2
- 2015/01/20 New version release Burst 1.2.1
- 2014/12/22 New version release Burst 1.2.0
- 2014/11/04 New version release 1.1.5
- 2014/10/18 New version release 1.1.4
- 2014/10/04 Escrow transactions enabled
- 2014/09/27 New version release 1.1.3
- 2014/09/14 New version release 1.1.2
- 2014/09/13 Stuck transactions statement
- 2014/09/13 New version release 1.1.1
- 2014/09/09 New version release 1.1.0
- 2014/08/31 V2 mining pool now up
- 2014/08/27 New version release 1.0.3
- 2014/08/20 First pool (v1) now up
- 2014/08/17 New version release 1.0.2
- 2014/08/16 Statement regarding the difficulty adjustment
- 2014/08/11 Statement regarding The pool situation

## Links

For further information, please visit the following pages.

### Home
https://web.burst-team.us

### Block-Explorer
http://burstcoin.biz

### Forum
https://forums.burst-team.us

### Bitcointalk
https://bitcointalk.org/index.php?topic=1541310 *(New unmoderated)*

https://bitcointalk.org/index.php?topic=1323657 *(Alternative moderated)*

https://bitcointalk.org/index.php?topic=731923 *(Original unmoderated)*

### Related repositories
https://github.com/BurstProject *Original/Forked Burstcoin, ATDebugger, ATAssembler, POCMiner (Proof of concept plotter/miner), etc.*

https://github.com/IceBurst/Burst *Burst for Android*

https://github.com/SOELexicon *Burst AIO Wallet*

https://github.com/dawallet/ *Burstcoin Win Client, Android App*

https://github.com/Blagodarenko  *Blago's Windows Miner, PlotsChecker, etc.*

https://github.com/de-luxe *GPU assisted jMiner, Faucet Software, Address generator*

https://github.com/BurstTools/BurstSoftware *Windows Plot Generator for SEE4/AVX2*

https://github.com/bhamon *gpuPlotGenerator, BurstMine (graphical plotter/miner)*

https://github.com/kartojal *GUI for Dcct Tools, GUI for gpuPlotGenerator (linux)*

https://github.com/Kurairaito *Burst Plot Generator by Kurairaito*

https://github.com/Mirkic7 *Improved Linux Burst Plotter / optimizer / miner (linux)*

https://github.com/uraymeiviar *C Miner, Pool, Block Explorer, Plot Composer (linux)*

https://github.com/mrpsion/burst-mining-system *Web interface for Plotting and Mining*

### Additional Software
https://forums.burst-team.us/category/9/burst-software
