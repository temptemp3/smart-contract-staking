# Smart Contract Staking

Implementation of smart contract for staking solution described in document [Smart Contract Staking - Voi Foundation - 20231218](https://docs.google.com/document/d/17-Hvqp7ZndS0G2CrJEui_hFIHZksBALYNU7CqKvnyxM/edit#heading=h.rhnx1imq9wmf).

## requirements

- algokit >= version 2.0.3
- python >= 3.12.3
- node >= v20.12.2

## commands

### build all 
```
algokit compile py contract.py
algokit generate client SmartContractStaking.arc32.json --language typescript --output SmartContractStakingClient.ts
algokit generate client SmartContractStaking.arc32.json --language python --output SmartContractStakingClient.py
```

