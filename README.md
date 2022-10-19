# Zeeka Incentivized Testnet
Zeeka Network Ödüllü Node Testnet

![image](https://user-images.githubusercontent.com/98783018/196802728-6f5df2ba-94c4-4d68-aa50-9037871f3d04.png)


```
2 CPU
4 GB RAM
50GB of storage (SSD or NVME)

Sisteminiz ne kadar güçlü ise o kadar fazla coin kazarsınız.
```

Cmake kurulumu

```
sudo apt install -y libssl-dev cmake
sudo apt install screen
```

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```

kodu klonla

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```

Kaynak

```
source "$HOME/.cargo/env"
```

Dosya oluştur ve kurulum yap

```
cd bazuka
sudo apt install -y g++
cargo install --path .
```

Screen kurulumu

```
screen -S bazuka

```
Seed Giriyoruz

```
bazuka init --seed cryptoloss --network chaos --node 127.0.0.1:8765
```

Nodu kuruyoruz

```
bazuka node --listen 0.0.0.0:8765 --external IPADRESİ:8765
  --network chaos --db ~/.bazuka-chaos \ 
  --bootstrap [bootstrap node 1] --bootstrap [bootstrap node 2] \ 
  --discord-handle "discordismi"
```


Hayırlı olsun. Destek olmak amacıyla beni githubdan takip ederseniz çok sevinirim.
