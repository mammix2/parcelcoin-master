# Parcelcoin [PARL] Integration/Staging Tree
http://parcelcoin.eu/

## What is ParcelCoin? 
Parcelcoin is like Bitcoin, but based on Litecoin.
http://parcelcoin.eu/

## License.
ParcelCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions.
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How many Parcelcoin can exist?
TBD

### How get parl?
Scrypt Proof of Work

1 Minute Block Targets, 3 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-1,000,000 Parcelcoin Reward

100,001 — 200,000: 0-500,000 Parcelcoin Reward

200,001 — 300,000: 0-250,000 Parcelcoin Reward

300,001 — 400,000: 0-125,000 Parcelcoin Reward

400,001 — 500,000: 0-62,500 Parcelcoin Reward

500,001 - 600,000: 0-31,250 Parcelcoin Reward

600,000+ — 10,000 Reward (flat)

### how to make make parcelcoind on linux or UNIX

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Parcelcoin ports
RPC 9315
P2P 9316
