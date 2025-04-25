# Inichain (Initverse)

first register here : [inichain](https://candy.inichain.com?invite=0xd40D965686aE9599693d32D12a481dA0C1d893Dc)

Download Installer

```bash
wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64
```

Change Permission to downloaded file

```bash
chmod +x iniminer-linux-x64
```

Create a Screen for it

```bash
screen -S inichain
```

replace <YOUR_WALLET_ADDRESS> with your wallet address and Run Miner.

please note that you should limit miner to use less CPU cores than maximum cores so that it can operate normal for other nodes.

for example if your VPS has 8 CPU cores, limit it to use just four CPU threads for mining by appending below commands:

```bash
--cpu-devices 1 --cpu-devices 2 --cpu-devices 3 --cpu-devices 4
```

so the final command for running miner should be look likes:

```bash
./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672 --cpu-devices 1 --cpu-devices 2 --cpu-devices 3 --cpu-devices 4
```

Detach from screen by CTL + ALT + D

## check status

Check your Minner Status: [https://genesis-testnet.yatespool.com](https://genesis-testnet.yatespool.com/)

## Join our Telegram Channel

For more bots and tutorials you can join our Telegram channel

[**UbuntuForNodes**](https://t.me/ubuntufornodes)

also you can follow me on [X(iamshaho)](https://x.com/iamshaho)
