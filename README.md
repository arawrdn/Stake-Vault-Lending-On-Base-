# Base Stake Vault Smart Contract

This repository contains a simple ERC20 staking vault smart contract that can be deployed on the **Base Network** using Remix IDE.

## Steps to Deploy

1. **Open Remix IDE**
   - Go to: [https://remix.ethereum.org](https://remix.ethereum.org)

2. **Create New File**
   - File path: `contracts/Vault.sol`
   - Paste the smart contract code from `Vault.sol`.

3. **Compile Contract**
   - Compiler: Solidity 0.8.20
   - Enable optimization (optional)
   - Click **Compile Vault.sol**

4. **Deploy Contract**
   - Environment: `Injected Web3` (connect your wallet, e.g., MetaMask)
   - Network: Base Testnet/Mainnet
   - Constructor parameter: Staking token address (ERC20 token)
   - Click **Deploy**
   - Confirm the transaction in your wallet

5. **Interact with Contract**
   - Use Remix **Deployed Contracts** tab
   - `stake(amount)` → Approve and stake your ERC20 tokens
   - `withdraw(amount)` → Withdraw your stake plus reward

## Notes
- This is a simplified example for testing.
- Reward is calculated as a fixed percentage.
- For production, always audit contracts and consider security risks.


