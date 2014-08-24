coinfetch
=========

See [INSTALL](INSTALL) for installation instructions.

Using `coinfetch`
-----------------

coinfetch takes two arguments from the command line, and returns a conversion 
factor.

The arguments are the three (or sometimes four) letter identifiers of various 
currencies.

Many (but not all) pairs of coins can be used.

Example: `$ coinfetch doge btc`

The above example will return the amount of Bitcoin that can currently be bought
with one Dogecoin. 

If the coins are reversed (e.g. `$ coinfetch btc doge`), the amount of Dogecoin
that can currently be bought with one Bitcoin will be returned.

As of version 2.x, you may optionally add a third argument before the first
currency in order to multiply that amount.

Example: `$ coinfetch 1000 doge usd`

The above example will return the value of 1000 DOGE in USD.

Licensing
---------

This script is [free software](http://gnu.org/philosophy/free-sw.html), licensed
under the terms of the MIT license. See [LICENSE](LICENSE) for more information.
