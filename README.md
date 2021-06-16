

- X11 algorithm
- PoW/PoS(Hybrid)
- Shedule and fixed PoS rewards
- Min stake age: 4 hours
- Max stake age: 30 days
- Block time: 2 mins

How compile coind and qt wallet.

sudo apt-get update
sudo apt-get upgrade

sudo apt-get install build-essential libboost-all-dev libssl-ocaml-dev libssl1.0-dev git libminiupnpc-dev  libdb5.3++-dev libtool autotools-dev automake pkg-config libssl1.0-dev libevent-dev bsdmainutils python3 libqt4-dev  libqrencode-dev qrencode libdb++-dev


git clone https://github.com/ruvex/SteepCoin
cd SteepCoin/src/leveldb
chmod +x build_detect_platform
cd ..
make -f makefile.unix
cd ..
qmake
make

