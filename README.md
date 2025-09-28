# Simple Blockchain (Go)

A simple blockchain implementation in **Go** built from scratch to explore how blockchains work under the hood.
This project demonstrates fundamental blockchain concepts such as blocks, transactions, proof of work, and persistence.

## Features

* Basic blockchain data structure (blocks linked by hashes)
* Proof-of-Work consensus
* Transaction inputs and outputs
* Block & chain validation
* CLI commands for interacting with the blockchain
* Data persistence with BoltDB (or in-memory option)

## Tech Stack

* Language: Go (>= 1.17)
* Database: BoltDB (key-value store)
* Architecture: Modular, clean, with CLI interface

## Installation

Clone the repository:

```bash
git clone https://github.com/GeraldiAxel/blockchain-go.git
cd blockchain-go
```

Build the project:

```bash
go build -o blockchain
```

## Usage

Run the CLI:

```bash
./blockchain
```

Example commands:

```bash
# Create a new blockchain and mine the genesis block
./blockchain create -address YOUR_WALLET_ADDRESS

# Add a block with transactions
./blockchain send -from Alice -to Bob -amount 10

# Print the full blockchain
./blockchain print
```

## Learning Objectives

This project is part of my personal learning journey in **distributed systems** and **cryptography**.
Through building this project, I deepened my understanding of:

* Hashing & Merkle trees
* Proof-of-Work mechanics
* UTXO model
* Transaction validation
* Persistent storage for blockchains
