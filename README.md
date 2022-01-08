AnotherScryptCoin
=====================================
1/7/22 - I have resurrected this project, as I now have a free server to run a node on, enjoy!
<br>
<br>
What is AnotherScryptCoin?
----------------

AnotherScryptCoin is exactly what it says it is, It's based off of Litecoin (source 0.18) and is slightly "faster". This is mostly just a fun project. Many things likely still say "Litecoin" in docs and other areas, I didn't fork Litecoin and removed the original .git folder because that caused issues when trying to push.

<b>Website: <a href="https://asc.cash">asc.cash</a></b>

<b>Explorer: <a href="http://explorer.asc.cash">explorer.asc.cash</a></b>

Port to forward for running a node: 7143

IMPORTANT: If no blocks are mined after a certain period of time, the wallets will be stuck at "Syncing Headers" despite being connected, in order to fix this, just mine a block.

MINING: When mining with cpuminer (minerd) or similar tools be sure to use a native segwit bech32 address (check the box when creating under receive tab), otherwise your coins will end up in some other type of address, and I have no idea how to get them out.

License
-------

AnotherScryptCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Litecoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
