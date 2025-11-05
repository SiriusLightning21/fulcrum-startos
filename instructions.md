# Fulcrum

A fast & nimble SPV server for Bitcoin Cash, Bitcoin BTC, and Litecoin.

## Configuration

Select your Bitcoin node as a backend. Currently, Bitcoin Core is supported, with options for mainnet or testnet.

## Usage

After configuring, simply "Start" the service. This will begin syncing your indexer. This may take quite some time, up to 1-2 days, depending on your hardware.

> **_NOTE:_** If you are migrating from Fulcrum 1.11.1 to Fulcrum 2.0.0 be sure to STOP Fulcrum before you update. The database needs an update and that check is executed after installation during configuration and pressing START. If you do not STOP Fulcrum 1.11.1, after installation the new 2.0.0 instance will attempt to start up prematurely, which creates an update failure.
