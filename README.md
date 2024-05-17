# ERC20 and Vault Smart Contracts

## Introduction

Welcome to the ERC20 and Vault smart contracts repository. This project includes two primary smart contracts:

1. **ERC20 Token Contract**: Implements the ERC20 token standard for creating fungible tokens.
2. **Vault Contract**: Provides a secure vault for storing ERC20 tokens, allowing deposits and withdrawals.

## ERC20 Token Contract

The ERC20 Token Contract adheres to the ERC20 standard, offering a straightforward and robust implementation for managing fungible tokens on the Ethereum blockchain.

### Key Features

- **Standard ERC20 Interface**: Includes essential ERC20 functions like `transfer`, `approve`, and `transferFrom`.
- **Minting and Burning Capabilities**: Allows for tokens to be minted and burned.
- **Ownership Control**: Utilizes the Ownable pattern for access control.

### Main Functions

- `name()`: Retrieves the token name.
- `symbol()`: Retrieves the token symbol.
- `decimals()`: Retrieves the number of decimal places.
- `totalSupply()`: Gets the total token supply.
- `balanceOf(address account)`: Gets the token balance of an account.
- `transfer(address recipient, uint256 amount)`: Transfers tokens to a specified recipient.
- `approve(address spender, uint256 amount)`: Approves a spender to use a specified amount of tokens.
- `transferFrom(address sender, address recipient, uint256 amount)`: Transfers tokens from one account to another based on an allowance.
- `allowance(address owner, address spender)`: Retrieves the remaining number of tokens that a spender is allowed to use on behalf of the owner.

## Vault Contract

The Vault Contract is designed for securely storing ERC20 tokens, allowing users to deposit and withdraw their tokens easily.

### Key Features

- **Deposit and Withdrawal**: Users can deposit and withdraw ERC20 tokens.
- **User Balance Tracking**: Keeps track of token balances for each user.
- **Token Security**: Ensures that only valid ERC20 tokens are managed by the vault.

### Main Functions

- `deposit(uint256 amount)`: Deposits a specified amount of ERC20 tokens into the vault.
- `withdraw(uint256 amount)`: Withdraws a specified amount of ERC20 tokens from the vault.
- `balanceOf(address account)`: Retrieves the token balance of an account within the vault.
## thank you 
