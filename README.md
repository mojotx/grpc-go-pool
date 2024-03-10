# grpc-go-pool

![Go Coverage](https://raw.githubusercontent.com/mojotx/grpc-go-pool/master/coverage_badge.png)
[![GoDoc](https://godoc.org/github.com/mojotx/grpc-go-pool?status.svg)](https://godoc.org/github.com/mojotx/grpc-go-pool)

This package aims to provide an easy to use and lightweight GRPC connection pool.

Please note that the goal isn't to replicate the client-side load-balancing feature of the official grpc package: the goal is rather to have multiple connections established to one endpoint (which can be server-side load-balanced).
