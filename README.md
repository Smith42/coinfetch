coinfetch
=========

A python script that is capable of printing almost all cryptocoin prices in terms 
of other coins (and fiat money).

Using coinfetch
---------------

coinfetch takes two arguments from the command line, and returns a conversion factor.

The arguments are the three (or sometimes four) letter identifiers of various currencies.

Many (but not all) pairs of coins can be used.

Example: <code>$ coinfetch doge btc</code>

The above example will return the amount of Bitcoin that can currently be bought with one
Dogecoin. 

If the coins are reversed (e.g. <code>$ coinfetch btc doge</code> ), the amount of Dogecoin
that can currently be bought with one Bitcoin will be returned.

Resolving Dependencies
----------------------
This script requires python3 and python3-requests.

Python3 can be installed through your distrubution's package manager, or downloaded from 
[python's website](https://www.python.org/).

Python3-requests can be installed through pip:

<code>$ pip install requests</code>

Python3-requests also have installation instructions on their 
[website](http://docs.python-requests.org/en/latest/user/install/#install).

Installation
------------

To install coinfetch:

<code>$ chmod +x ./coinfetch && sudo cp ./coinfetch /usr/local/bin/</code>

Licensing
---------

This script is [free software](http://gnu.org/philosophy/free-sw.html), licensed
under the terms of the MIT license. See [LICENSE](LICENSE) for more information.
