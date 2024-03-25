Mainnet mina docker setup

Quick start Mina block producer with docker-compose

1. Get this repo
```
git clone https://github.com/LexPrime/mina-mainnet-docker
cd mina-mainnet-docker
```

2. Use keygen.sh for generating new private key

```
./keygen.sh
```

3. Copy sample.env to .env and add your variables

```
cp sample.env .env
./start.sh
```
