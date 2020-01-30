# goipp

[![godoc.org](https://godoc.org/github.com/alexpevzner/goipp?status.svg)](http://godoc.org/github.com/alexpevzner/goipp)
![GitHub](https://img.shields.io/github/license/alexpevzner/goipp)
[![Go Report Card](https://goreportcard.com/badge/github.com/alexpevzner/goipp)](https://goreportcard.com/report/github.com/alexpevzner/goipp)

The goipp library is fairly complete implementation of IPP core protocol in
pure Go. Essentially, it is  IPP messages parser/composer. Transport is
not implemented here, because Go standard library has an excellent built-in
HTTP client, and it doesn't make a lot of sense to wrap it here.

High-level requests, like "print a file" are also not implemented, only the
low-level stuff.

All documentation is on godoc.org -- follow the link above. Pull requests
are welcomed, assuming they don't break existing API.
