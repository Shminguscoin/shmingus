<h1 align="center">
Shminguscoin Core [SHM]
<br/><br/>
<img src="https://avatars.githubusercontent.com/u/104106315?s=200&v=4" alt="Shminguscoin" width="200"/>
</h1>

## What is Shminguscoin?

Shminguscoin is a cryptocurrency like Bitcoin, although it does not use SHA256 as its proof of work (POW). Taking development cues from Dogecoin and Litecoin, Shminguscoin currently employs a simplified variant of scrypt.

## Usage 

To start your journey with Shminguscoin Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Shminguscoin Core is self-documenting and can be browsed with `shminguscoin-cli help`, while detailed information for each command can be viewed with `shminguscoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

##License

Shminguscoin is released under the terms of the MIT license. See  [COPYING](https://github.com/bunkercoin-project/bunkercoin/blob/master/COPYING)  for more information or see  [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT).

## Development and contributions

Development is ongoing and the development team as well as other volunteers can freely work in their own trees and submit pull requests when features or bug fixes are ready.

## Not Frequently Asked Questions

### How many Shminguscoin's can exist?

The maximum supply of Shminguscoin will never go above 69 billion (nice)

### How can I mine Shminguscoin?

Shminguscoin uses a simplified variant of the scrypt key derivation function as its proof of work with a target time of one minute per block and difficulty readjustment after every block. The block rewards are fixed and halve every 210,000 blocks. To get Shminguscoin, you have to use a Scrypt miner and
follow the instructions on https://shming.us/mining

### How can I help the network?

The solid best way is to mine. You can use any guide and miner that supports scrypt coins like Dogecoin, Litecoin, etc.

### Want to know the ports? Well here is the place to be!

| Function | mainnet |
| :------- | ------: | 
| P2P      |   64669 |
| RPC      |   64644 |
