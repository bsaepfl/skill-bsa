# Environment Setup

These steps apply to any event. If `event.md` lists a starter template, its README comes first. Use this file for what the README does not cover.

## 1. Wallet

- Install a browser wallet that supports the target chain.
- Create a new wallet only for the hackathon. Never use a wallet that holds real funds.
- Add the testnet of the target chain to the wallet.

## 2. Testnet Funds

- Get test tokens from a faucet for the target testnet.
- Use the faucet that the chain's official documentation lists. Unofficial faucets can be scams.
- Test tokens have no value. Never pay for them.

## 3. Toolchain

For EVM chains (Ethereum and compatible chains), Foundry is one common choice:

```sh
forge init my-project   # create a project
cd my-project
forge build             # compile contracts
forge test              # run tests
```

For other chains, follow the official quickstart of that chain.

## 4. Deploy to a Testnet

- Store the deployer key in an encrypted keystore, not in source code. With Foundry: `cast wallet import <name> --interactive`, then pass `--account <name>` to deploy commands.
- Get an RPC URL for the testnet from the chain's documentation or an RPC provider. Keep the URL in a `.env` file that git ignores.
- After deployment, record the contract address and its block explorer link. The submission needs them.

## 5. Common Problems

- "Insufficient funds": the deployer address has no test tokens. Use the faucet.
- Wrong network: the wallet or the RPC URL points to a different chain than the contract.
- Contract changes not visible in the front end: the front end uses an old contract address or ABI.
