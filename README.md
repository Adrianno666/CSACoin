csacoin 1.0.12
=============

What is csacoin?
--------------

[csacoin](https://z.cash/) is an implementation of the "Zerocash" protocol.
Based on Bitcoin's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. Technical details are available
in our [Protocol Specification](https://github.com/csacoin/zips/raw/master/protocol/protocol.pdf).

This software is the csacoin client. It downloads and stores the entire history
of csacoin transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

Security Warnings
-----------------

See important security warnings in
[doc/security-warnings.md](doc/security-warnings.md).

**csacoin is experimental and a work-in-progress.** Use at your own risk.

Deprecation Policy
------------------

This release is considered deprecated 16 weeks after the release day. There
is an automatic deprecation shutdown feature which will halt the node some
time after this 16 week time period. The automatic feature is based on block
height and can be explicitly disabled.

Where do I begin?
-----------------
We have a guide for joining the main csacoin network:
https://github.com/csacoin/csacoin/wiki/1.0-User-Guide

### Need Help?

* See the documentation at the [csacoin Wiki](https://github.com/csacoin/csacoin/wiki)
  for help and more information.
* Ask for help on the [csacoin](https://forum.z.cash/) forum.

Participation in the csacoin project is subject to a
[Code of Conduct](code_of_conduct.md).

Building
--------

Build csacoin along with most dependencies from source by running
./zcutil/build.sh. Currently only Linux is officially supported.

License
-------

For license information see the file [COPYING](COPYING).
