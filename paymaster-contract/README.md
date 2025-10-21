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

```
Deployed to: 0x5D0fee2d4159F102C4EDc81187A9fb2BFc6C5a40
Transaction hash: 0xfe36afc30c21cb8bfdbe348fd26b4fa04fdcd12bb74ebc8d82dc6025fdf6f35f
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Frontend

```shell
$ npm create vite@latest paymaster-frontend -- --template react
```
