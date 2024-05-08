# SGX Demo with Gramine

Contains a Makefile and a manifest template for running a simple
MyService program in Gramine. It can be used as a sanity test for your
Gramine installation as well as a simple example of a memory hacking.

# Building

## Building for Linux

Run `make` (non-debug) or `make DEBUG=1` (debug) in the directory.

## Building for SGX

Run `make SGX=1` (non-debug) or `make SGX=1 DEBUG=1` (debug) in the directory.

# Run MyService with Gramine

Without SGX:
```sh
gramine-direct myservice
```

With SGX:
```sh
gramine-sgx myservice
```
