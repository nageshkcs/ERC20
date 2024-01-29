# GoldToken 

## Introduction

GoldToken is a Solidity smart contract for creating a customizable ERC20 token on the Ethereum blockchain. This contract is designed to provide basic functionalities of an ERC20 token along with additional features such as minting, burning, and increasing the total token supply.

## Features

### ERC20 Compliance

GoldToken contract implements the ERC20 standard, which ensures compatibility with wallets, exchanges, and other services that support ERC20 tokens. This means that the token can be easily integrated into various decentralized applications (dApps) and blockchain ecosystems.

### Minting

The contract owner has the ability to mint new tokens and assign them to specific addresses. This functionality is useful for distributing tokens during token sales, airdrops, or as rewards.

### Burning

Token holders can burn their own tokens, effectively reducing the total supply. Burning tokens can be used for various purposes such as token buybacks, reducing inflation, or implementing deflationary mechanisms.

### Total Supply Boost

The contract owner can increase the total token supply by minting additional tokens. This feature provides flexibility in managing the token economy and adjusting the token supply according to the project's needs.

## Getting Started

To deploy and interact with the GoldToken contract, follow these steps:

1. **Compile Contract**: Use a Solidity compiler (e.g., Remix, Hardhat, Truffle) to compile the GoldToken.sol file.

2. **Deploy Contract**: Deploy the compiled contract to the Ethereum blockchain using a compatible wallet or development environment. Ensure that you specify the necessary constructor parameters such as token title, symbol, initial magnitude, and initial owner address.

3. **Interact with Contract**: Once deployed, you can interact with the GoldToken contract using Ethereum wallets or custom scripts. Use functions such as `mintUnits`, `burnUnits`, `boostTotalSupply`, and `transfeunits` to manage token minting, burning, and transfers.

## Author

Nagesh KC 

## License

GoldToken contract is released under the MIT License. See the [LICENSE](LICENSE) file for more details.

