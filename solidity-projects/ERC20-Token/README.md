# ERC20 Token - MyToken

This is a simple ERC20 token written in Solidity.  
It follows a basic structure of total supply, transfer, approve, and transferFrom.

## Features
- Token Name: DasToken
- Symbol: DAS
- Decimals: 18
- Initial Supply set in constructor

## How to Deploy
1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new file `MyToken.sol`.
3. Paste the code and compile using Solidity 0.8.x.
4. Deploy the contract → enter initial supply (e.g., `1000`).
5. Use `transfer` to send tokens, `approve` + `transferFrom` for allowance.

## Example Usage
- Deploy with 1000 tokens.
- Balance of deployer = 1000 DAS.
- Transfer 100 DAS to another address → their balance updates.
