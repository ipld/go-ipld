<div align="center">
  <a href="https://ipld.io"><img src="https://ipld.io/img/ipld-logo.png" alt="IPLD hex logo" /></a>
</div>

# The entry point repo for the Golang implementation of the IPLD

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://protocol.ai)
[![](https://img.shields.io/badge/project-ipld-blue.svg?style=flat-square)](http://ipld.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![](https://img.shields.io/badge/pm-waffle-blue.svg?style=flat-square")](https://waffle.io/ipld/go-ipld)

> The JavaScript implementation of the IPLD, InterPlanetary Linked-Data

## Project Status

[![Throughput Graph](https://graphs.waffle.io/ipld/go-ipld/throughput.svg)](https://waffle.io/ipld/go-ipld/metrics/throughput)

[**`Weekly Core Dev Calls`**](https://github.com/ipfs/pm/issues/674)

## Packages

> This table is generated using the module [`package-table`](https://github.com/ipfs-shipyard/package-table) with `package-table --data=package-list.json`.

Listing of dependencies from the IPLD ecosystem.

| Name | CI/Travis | CI/Jenkins | Coverage |
| ---------|---------|---------|--------- |
| **IPLD Formats** |
| [`ipld-format`](//github.com/ipfs/go-ipld-format) | [![Travis CI](https://travis-ci.org/ipfs/go-ipld-format.svg?branch=master)](https://travis-ci.org/ipfs/go-ipld-format) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-ipld-format/master)](https://ci.ipfs.team/job/ipfs/job/go-ipld-format/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-ipld-format/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-ipld-format) |
| [`ipld-cbor`](//github.com/ipfs/go-ipld-cbor) | [![Travis CI](https://travis-ci.org/ipfs/go-ipld-cbor.svg?branch=master)](https://travis-ci.org/ipfs/go-ipld-cbor) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-ipld-cbor/master)](https://ci.ipfs.team/job/ipfs/job/go-ipld-cbor/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-ipld-cbor/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-ipld-cbor) |
| [`ipld-git`](//github.com/ipfs/go-ipld-git) | [![Travis CI](https://travis-ci.org/ipfs/go-ipld-git.svg?branch=master)](https://travis-ci.org/ipfs/go-ipld-git) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-ipld-git/master)](https://ci.ipfs.team/job/ipfs/job/go-ipld-git/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-ipld-git/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-ipld-git) |
| [`ipld-eth`](//github.com/ipfs/go-ipld-eth) | [![Travis CI](https://travis-ci.org/ipfs/go-ipld-eth.svg?branch=master)](https://travis-ci.org/ipfs/go-ipld-eth) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-ipld-eth/master)](https://ci.ipfs.team/job/ipfs/job/go-ipld-eth/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-ipld-eth/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-ipld-eth) |
| [`ipld-btc`](//github.com/ipfs/go-ipld-btc) | [![Travis CI](https://travis-ci.org/ipfs/go-ipld-btc.svg?branch=master)](https://travis-ci.org/ipfs/go-ipld-btc) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-ipld-btc/master)](https://ci.ipfs.team/job/ipfs/job/go-ipld-btc/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-ipld-btc/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-ipld-btc) |
| [`ipld-zcash`](//github.com/ipfs/go-ipld-zcash) | [![Travis CI](https://travis-ci.org/ipfs/go-ipld-zcash.svg?branch=master)](https://travis-ci.org/ipfs/go-ipld-zcash) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-ipld-zcash/master)](https://ci.ipfs.team/job/ipfs/job/go-ipld-zcash/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-ipld-zcash/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-ipld-zcash) |
| **Data Types (non IPLD specific)** |
| [`multihashes`](//github.com/multiformats/go-multihash) | [![Travis CI](https://travis-ci.org/multiformats/go-multihash.svg?branch=master)](https://travis-ci.org/multiformats/go-multihash) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=multiformats/go-multihash/master)](https://ci.ipfs.team/job/multiformats/job/go-multihash/job/master/) | [![codecov](https://codecov.io/gh/multiformats/go-multihash/branch/master/graph/badge.svg)](https://codecov.io/gh/multiformats/go-multihash) |
| [`cid`](//github.com/ipfs/go-cid) | [![Travis CI](https://travis-ci.org/ipfs/go-cid.svg?branch=master)](https://travis-ci.org/ipfs/go-cid) | [![jenkins](https://ci.ipfs.team/buildStatus/icon?job=ipfs/go-cid/master)](https://ci.ipfs.team/job/ipfs/job/go-cid/job/master/) | [![codecov](https://codecov.io/gh/ipfs/go-cid/branch/master/graph/badge.svg)](https://codecov.io/gh/ipfs/go-cid) |

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipld/go-ipld/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

MIT
