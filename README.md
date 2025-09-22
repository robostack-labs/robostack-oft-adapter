# RoboStack OFTAdapter

## EID
BASE: 30184
PEAQ: 30302

## Deployed Contracts

| Network | Contract     | Address                                    |
|---------|--------------|--------------------------------------------|
| BASE    | ERC20        | 0x708c2B2eEb9578dFe4020895139E88F7654647Ff |
|         | MyOFTAdapter | 0xC6333bCF1257bFEE0235c288486b1522ea61BED8 |
| PEAQ    | MyOFT        | 0xFd9D1b4a0384396A595345886d1E1D8AbF439CEf |

## Usage

```shell
npx hardhat lz:oft:send --src-eid 30184 --dst-eid 30302 --amount 10 --to 0x5eE0F64543dCdfA4D857eEf3a2B7D85437E47dB4
```
