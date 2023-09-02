REDB Documentation
====================

Setup
---------------------
REDB is the name of both the original REDB client, and the peer-to-peer protocol / network it validates. It downloads and, by default, stores the entire history of REDB transactions, which requires about 2.8mb as of Nov 8, 2018. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few moments to a day or more.

Download REDB from either [redblock.org](https://redblock.org/releases/) or [GitHub](https://github.com/redblock/redblock).


Running
---------------------
The following are some helpful notes on how to run REDB on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/redblock-qt` (GUI) or
- `bin/redblockd` (headless)

### Windows

Unpack the files into a directory, and then run redblock-qt.exe.

### macOS

Drag REDB to your applications folder, and then run REDB.

### Need Help?

Likely, the information you need can be found in the existing Bitcoin literature:

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#bitcoin](http://webchat.freenode.net?channels=bitcoin) on Freenode. If you don't have an IRC client, use [webchat here](http://webchat.freenode.net?channels=bitcoin).
* Ask for help on [BitcoinTalk](https://bitcointalk.org/)

Building
---------------------
The following are developer notes on how to build Bitcoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The REDB repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Bitcoin Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Development & Technical Discussion board](https://bitcointalk.org/index.php?board=6.0).
* Discuss project-specific development on #bitcoin-core-dev on Freenode. If you don't have an IRC client, use [webchat here](http://webchat.freenode.net/?channels=bitcoin-core-dev).
* Discuss general Bitcoin development on #bitcoin-dev on Freenode. If you don't have an IRC client, use [webchat here](http://webchat.freenode.net/?channels=bitcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [REDB's bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
