# Go Keyless

[![Build Status](https://travis-ci.org/cloudflare/gokeyless.png?branch=master)](https://travis-ci.org/cloudflare/gokeyless)
[![Coverage Status](https://coveralls.io/repos/cloudflare/gokeyless/badge.svg?branch=master)](https://coveralls.io/r/cloudflare/gokeyless?branch=master)
[![GoDoc](https://godoc.org/github.com/cloudflare/gokeyless?status.png)](https://godoc.org/github.com/cloudflare/gokeyless)
## Keyless SSL implementation in Go

Go Keyless is an implementation CloudFlare's [Keyless SSL](https://blog.cloudflare.com/keyless-ssl-the-nitty-gritty-technical-details/) Protocol in Go. It is provided as
an upgrade to the previous [C implementation](https://github.com/cloudflare/keyless). **NOTE: CURRENTLY IN ALPHA TESTING**

### Installation
Go Keyless requires Go 1.5 (currently in beta). Binary distributions can be found at [golang.org/dl](https://golang.org/dl/), under `go1.5beta2`.

Installing the appropriate package for your operating system should leave you with a  [working Go
installation](http://golang.org/doc/install) and a properly set `GOPATH`.

```
# To download and build the server binary:
$ go install github.com/cloudflare/gokeyless/cmd/gokeyless/...
# For full source code:
$ go get -u github.com/cloudflare/gokeyless/...
$ cd $GOPATH/src/github.com/cloudflare/gokeyless/
```
