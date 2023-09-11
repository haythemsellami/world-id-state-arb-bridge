# world-id-state-arb-bridge

## Description

State bridge between the WorldID Ethereum mainnet deployment and WorldID Arbitrum network

## Development Progress

- [ ] Implementation: 
  - [X] ArbWorldID
    - [X] receiveRoot()
    - [X] setRootHistoryExpiry()
  - [ ] ArbStateBridge
    - [X] propagateRoot()
    - [ ] transferOwnershipArb()
    - [X] setRootHistoryExpiry()
- [ ] Tests:
  - [ ] Finish all ArbWorldID tests
  - [ ] Finish all ArbStateBridge tests

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```