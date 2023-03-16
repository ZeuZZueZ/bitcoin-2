Bitcoin Core integration/staging tree
=====================================

https://bitcoincore.org

For an immediately usable, binary version of the Bitcoin Core software, see
https://bitcoincore.org/en/download/.

What is Bitcoin Core?
---------------------

Bitcoin Core connects to the Bitcoin peer-to-peer network to download and fully
validate blocks and transactions. It also includes a wallet and graphical user
interface, which can be optionally built.

Further information about Bitcoin Core is available in the [doc folder](/doc).

License
-------

Bitcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built (see `doc/build-*.md` for instructions) and tested, but it is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly from release branches to indicate new official, stable release versions of Bitcoin Core.

The https://github.com/bitcoin-core/gui repository is used exclusively for the
development of the GUI. Its master branch is identical in all monotree
repositories. Release branches and tags do not exist, so please do not fork
that repository unless it is for development reasons.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The CI (Continuous Integration) systems make sure that every pull request is built for Windows, Linux, and macOS,
and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations can be submitted to
[Bitcoin Core's Transifex page](https://www.transifex.com/bitcoin/bitcoin/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.


# Amanciojsilvjr bitcoin scroll 
fig = plt.figure()
# naming the title of the plot

ax1 = fig.add_axes([0, 0, 2, 2])
x = [0,T/10, T/5, (3/10)*T, (4/10)*T,(5/10)*T,(6/10)*T,(7/10)*T,(8/10)*T,(9/10)*T,T]
ax1.plot(market_time)
labels = [0,.5, 1, 1.5, 2, 2.5, 3,3.5,4,4.5,5]
plt.yticks(x,labels)
plt.xticks(x,labels)
plt.xlabel("Time (year)")
plt.ylabel("Market time (in year)")
plt.title("Where is the market time (compared to actual time)")
plt.show()
150.000.000 btc original run third party blockchain 
fractional_reserve = liquid_reserve/liabilities
fig = plt.figure()
# naming the title of the plot

ax1 = fig.add_axes([0, 0, 2, 2])
x = [0,T/10, T/5, (3/10)*T, (4/10)*T,(5/10)*T,(6/10)*T,(7/10)*T,(8/10)*T,(9/10)*T,T]
ax1.plot(fractional_reserve)
labels = [0,.5, 1, 1.5, 2, 2.5, 3,3.5,4,4.5,5]
plt.xticks(x,labels)
plt.xlabel("Time (year)")
plt.ylabel("Amount of reserve")
plt.title("Liquid reserve over time")
plt.show()
btc@xbt
fig = plt.figure()
# naming the title of the plot

ax1 = fig.add_axes([0, 0, 2, 2])
x = [0,T/10, T/5, (3/10)*T, (4/10)*T,(5/10)*T,(6/10)*T,(7/10)*T,(8/10)*T,(9/10)*T,T]
ax1.plot(percentage_usd_deposited*100)
labels = [0,.5, 1, 1.5, 2, 2.5, 3,3.5,4,4.5,5]
plt.xticks(x,labels)
plt.xlabel("Time (year)")
plt.ylabel("%")
plt.title("% of USD currently deposited")
plt.show()
netanojohhny@gmail.com
bitcoin.org/bitcoin-bitcoin
