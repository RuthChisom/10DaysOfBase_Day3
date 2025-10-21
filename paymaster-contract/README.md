## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**


## Usage
### Build

```env
RPC_URL="https://sepolia.base.org"
```

### Deploy

```shell
forge create "src/Rewards.sol:RewardContract" --rpc-url "$RPC_URL" --broadcast --private-key "$PRIVATE_KEY" --value 0.00009ether
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```
