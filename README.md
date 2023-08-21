Mainnet mina docker setup

Quick start Mina block producer with docker-compose

```
git clone https://github.com/LexPrime/mina-mainnet-docker
cd mina-mainnet-docker
```

Use mina_keygen.sh for generating new private key

```
./mina_keygen.sh
```

Copy sample.env to .env and add your variables

```
cp sample.env .env
./start.sh
```
