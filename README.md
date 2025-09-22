# RoboStack OFTAdapter

## EID
BASE: 30184
PEAQ: 30302

## Deployed Contracts

| Network | Contract     | Address                                    |
|---------|--------------|--------------------------------------------|
| BASE    | ERC20        | 0x708c2B2eEb9578dFe4020895139E88F7654647Ff |
|         | MyOFTAdapter | 0x1Dbc47B0Fd3AdA6e4F8CcC5C619a2048c4Bd35C1 |
| PEAQ    | MyOFT        | 0x1Dbc47B0Fd3AdA6e4F8CcC5C619a2048c4Bd35C1 |

## Usage

```shell
npx hardhat lz:oft:send --src-eid 30184 --dst-eid 30302 --amount 10 --to 0x5eE0F64543dCdfA4D857eEf3a2B7D85437E47dB4
```
