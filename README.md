# ERC20 Token and Vault Contracts

This repository contains the Solidity code for ERC20 token and Vault contracts. These contracts are designed to provide functionalities for creating and managing ERC20 tokens as well as secure storage of assets in a vault.

## ERC20 Token Contract

The ERC20 Token contract implements the ERC20 standard, which allows for the creation of fungible tokens on the Ethereum blockchain. This contract provides functionalities for token transfers, approvals, and querying of token balances.


### Features:
- Transfer tokens between addresses.
- Approve spender to transfer tokens on behalf of the token owner.
- Transfer tokens from one address to another on behalf of the token owner (with approval).
- Get the balance of tokens for a specific address.

## Vault Contract

The Vault contract provides secure storage for assets (tokens or Ether) on the Ethereum blockchain. It allows users to deposit, withdraw, and transfer assets between addresses securely.

### Features:
- Deposit assets (tokens or Ether) into the vault.
- Withdraw assets from the vault.
- Transfer assets from one address to another within the vault.
- Get the balance of assets held in the vault for a specific address.

## License

This project is licensed under the [MIT License](LICENSE).

