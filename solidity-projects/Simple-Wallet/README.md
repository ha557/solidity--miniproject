# Simple Ether Wallet

This contract allows ETH deposits and withdrawals.  
Only the owner can withdraw.

## Features
- Owner is contract deployer
- Anyone can deposit ETH
- Owner can withdraw ETH
- View contract balance

## How to Deploy
1. Open Remix IDE.
2. Create file `SimpleWallet.sol`.
3. Paste code and compile.
4. Deploy (no parameters).
5. Use `deposit` → send ETH (in "Value" box).
6. Check balance with `getBalance`.
7. Withdraw using `withdraw(amount)`.

## Example Usage
- Deposit 1 ETH.
- `getBalance()` → 1 ETH.
- Withdraw 0.5 ETH → Balance reduces to 0.5 ETH.
