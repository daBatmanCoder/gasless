# Ethereum Transaction Relayer

## Description

This Python script is designed to interact with an Ethereum smart contract. It performs the following tasks:

1. Connects to a smart contract using its ABI and address.
2. Builds and signs a transaction using a given private key.
3. Relays the transaction through another Ethereum account.

The script uses the Web3.py library for Ethereum interaction and the RLP library for Ethereum transaction encoding and decoding.

## Prerequisites

- Python 3.x
- Web3.py
- RLP

## Installation

1. Clone this repository.
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory.
    ```bash
    cd your-repo-name
    ```

3. Install the required packages.
    ```bash
    pip install web3 rlp
    ```

## Configuration

Replace the following placeholders in the code:

- `contract_address`: The Ethereum address of the smart contract you're interacting with.
- `contract_abi`: The ABI of the smart contract.
- `public_key`: The Ethereum address from which you're sending the transaction.
- `private_key`: The private key corresponding to `public_key`.
- `relayer_private_key`: The private key of the relayer account.
- `relayer_public_key`: The Ethereum address of the relayer account.

## Usage

Run the script:

```bash
python your_script_name.py
