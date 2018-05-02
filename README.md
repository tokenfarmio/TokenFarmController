# TokenFarmController

Token Farm is a cloud based monitoring platform for crypto mining operations.  Simple to install and monitor on the go.  
No need to install in all machines.  Only install on 1 machine and you're good to go.  No need to change your miner settings. 
Token Farm automatically scans and logs changes to each miner and stores your data in the cloud so you can access anytime anywhere.
No need to setup VPN or flashing your miners.  Token Farm simply works with your existing mining software.

### Features:
* Automatic IP Scan of all antminer models
* Automatic IP Scan for NVIDIA and AMD GPU miners running Claymore.
* Automatic restart of Antminer miners based on Low Hash Thresholds.
* Automatic restart of GPU miners runing [Cyclenerd Linux GPU mining image](https://github.com/Cyclenerd/ethereum_nvidia_miner). 
* Remote Restart via web Dashboard or Mobile app for all Antminers.
* Monitor from the Web, iPhone or Android app.
* Temperature Tracking for individual Antminer and GPU Cards.
* Hash rate Tracking for individual GPU Cards and Antminers.
* Pool information tracking.
* Instant Notifications if pool information changes.
* Instant Notifications when miners go OFFLINE and when they are RESTORED.
* Alerts Log by individual miners to determine which miners need maintenance.
* Tag miners with Nicknames and Locations for easy identification and locating.

Simply your mining operation by monitoring with Token Farm. 

## Getting Started

1. Register for a Free Account at http://tokenfarm.io.  
2. You will receive you unique Token Farm API Key. 
3. [Download](http://199.59.98.137/crypto/setup.exe) - Latest version of TokenFarm Controller (windows) 
4. Install and follow instructions to enter your API Key.
5. Login to http://tokenfarm.io Dashboard
6. Download [iPhone](http://tokenfarm.io/wp-content/themes/landkit/library/images/download-on-the-app-store.svg) and [Android](https://play.google.com/store/apps/details?id=com.crmboost.tokenfarm) apps.

### Prerequisites

Currently controller only runs on Windows.  Linux controller will be coming soon.
Monitoring can be done from any modern web browser or via iPhone or Android app.

### Supported Miners

* All Bitmain Antminer models running CGMiner.
```
Tested with:
Antminer S3, S5, S7, S9, L3, L3+, D3, A3, M3.
```
* NVIDIA and AMD GPU miners running [Claymore Dual Miner](https://github.com/nanopool/Claymore-Dual-Miner).
```
Tested with:
NVIDIA GTX-1050, GTX-1060, GTX-1070, GTX-1080, P-106, P-104
AMD RX-470, RX-480, RX-570, RX-580 
```


## Important for Antminers

Token Farm Controller will scan your local network for available machines.  If you have changed the default password, you will have to click on the SETTINGS button and enter your password for each miner.   These passwords are only stored locally on your local windows machine and are never transmitted outside of your local network.

## Important for GPU Miners

When running Claymore, make sure your command that runs Claymore does not include the <i><b>-mport</b></i> option.  
If your GPU miners is running Claymore on Windows, make sure to set your Firewall to allow Claymore to communicate.

