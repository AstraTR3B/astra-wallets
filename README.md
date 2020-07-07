# astra-wallets

## Download the wallet
To download the wallet go to [releases](https://github.com/CryptoLover705/astra-wallets/releases) and click on the wallet you need 

Let it download and once it has downloaded open `Astracoin-qt.exe`, Let it load
## Astracoin.conf file details

Once you have run the wallet once close it and go to `C:\Users\<YOURUSER>\AppData\Roaming\AstraCoin`
Then right click and edit the `Astracoin.conf` file with a text editor (notepad++) and paste this into it

`PLEASE NOTE: Change the RPC USER and  RPC PASSWORD`
```
rpcuser=someuser
rpcpassword=somepassword
rpcallowip=127.0.0.1
port=4145
server=1
listen=1
daemon=1
txindex=1
logtimestamps=1
maxconnections=256
staking=1
addnode=104.168.145.22:4144
addnode=73.180.79.118:4144
addnode=144.202.23.87:4144
addnode=167.86.106.29:4144
addnode=207.180.250.120:4144
addnode=167.86.87.34:4144
```
Hit save, Navigate back to `Astracoin-qt.exe` and open it again you will have to allow for the wallet to sync up to the correct block 
