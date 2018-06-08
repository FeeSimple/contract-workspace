# Template for EOS smart contract workspace with VSC (Visual Studio Code)

## Reference source

[EOSFactory](http://eosfactory.io/) is a Python-based [EOS](https://eos.io) smart-contract development framework, created by [Tokenika](https://tokenika.io).

The goal is to achieve a similar functionality to Ethereum's [Truffle Framework](http://truffleframework.com/).

## Prerequisite

Please refer to [this](http://eosfactory.io/sphinx/build/html/tutorials/01.InstallingEOSFactory.html)

## Usage

Place all contract files into the folder `src`

#### 1. Command line

[Reference source](http://eosfactory.io/sphinx/build/html/tutorials/04.WorkingWithEOSContractsUsingEOSFactoryInVSC.html)

* `cd build`
* Configure: `cmake ..`
* Build: `make`
* Unit test: `ctest`

#### 2. Visual Studio Code

* Click `File` -> `Open` to import the workspace into VSC
* Click `Tasks` -> `Run Task ...` -> select the task (e.g. compile, build, unittest) to run
