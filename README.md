# Blockchain Visualizer

This visualizer is a more intuitive way to view and browse crypto transaction activity on the Binance Smart Chain (BSC) blockchain.

The goal of this project is to gain more experience with graphs, creating a GUI, and using an API.

![Status](https://img.shields.io/badge/status-alpha-orange)
![Java](https://img.shields.io/badge/java-11+-blue)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

---

## Features

### Current
Data can be pulled from [BscScan](https://bscscan.com), utilizing the API. Call limiting functionality has been implemented to comply with the BscScan rate limit of 5 calls/second (for free API keys). Note that no limiting has been done for the 100,000 calls/day limit.

API key is protected with a secrets file.

Wallets can be created and queried for current balance as well as any information contained by transaction data associated with the wallet (date, block executed on, sender, receiver, amounts, gas price, etc...).

### Planned
A user interface allowing the blockchain to be browsed. A wallet address can be entered and then a digraph is generated with the wallets as nodes and where the directed edges show the net direction that capital is flowing. Edge thickness indicates transaction volume, while color intensity (green) indicates capital flow.

<p align="center">
  <img src="blockchain_visualizer.png" alt="Blockchain Visualizer" width="800"/>
  <em>Interface Concept</em>
</p>

---

## Project Info
**Status:** Alpha (early development)  
**Author:** T. Stratton  
**Start Date:** 11-NOV-2023  
**License:** MIT License – see [LICENSE](./LICENSE)  
**Language:** Java 11.0+ (tested on 11.0)  
**Topics:** blockchain, crypto