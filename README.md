AnotherScryptCoin
=====================================
3/3/22 - Unfortunately I will be archiving this project for the last time, even with the network up and running, addresses are so unbelievably broken and I simply don't have time to run this anymore. I have uploaded the latest blocks and chainstate again <a href="https://github.com/Guinea1/AnotherScryptCoin/releases/download/1.0.0/ASC.zip">here</a>.
<br>
<br>
What is AnotherScryptCoin?
----------------

AnotherScryptCoin is exactly what it says it is, It's based off of Litecoin (source 0.18) and is slightly "faster". This is mostly just a fun project. Many things likely still say "Litecoin" in docs and other areas, I didn't fork Litecoin and removed the original .git folder because that caused issues when trying to push.

Port to forward for running a node: 7143

IMPORTANT: If no blocks are mined after a certain period of time, the wallets will be stuck at "Syncing Headers" despite being connected, in order to fix this, just mine a block.

MINING: When mining with cpuminer (minerd) or similar tools be sure to use a native segwit bech32 address (check the box when creating under receive tab), otherwise your coins will end up in some other type of address, and I have no idea how to get them out.

License
-------

AnotherScryptCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Litecoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
