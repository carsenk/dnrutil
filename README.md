dnrutil
=======

[![Build Status](http://img.shields.io/travis/carsenk/dnrutil.svg)](https://travis-ci.org/carsenk/dnrutil) 
[![Coverage Status](http://img.shields.io/coveralls/carsenk/dnrutil.svg)](https://coveralls.io/r/carsenk/dnrutil?branch=master) 
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/carsenk/dnrutil)

Package dnrutil provides Denarius-specific convenience functions and types.
A comprehensive suite of tests is provided to ensure proper functionality.  See
`test_coverage.txt` for the gocov coverage report.  Alternatively, if you are
running a POSIX OS, you can run the `cov_report.sh` script for a real-time
report.

This package was developed for dnrd, an alternative full-node implementation of
Denarius based on btcd, which is under active development by Conformal.
Although it was primarily written for dnrd, this package has intentionally been
designed so it can be used as a standalone package for any projects needing the
functionality provided.

## Installation and Updating

```bash
$ go get -u github.com/carsenk/dnrutil
```

## License

Package dnrutil is licensed under the [copyfree](http://copyfree.org) ISC
License.
