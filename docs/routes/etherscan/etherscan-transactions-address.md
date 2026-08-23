# Etherscan - 转账追踪

## Coverage
`index-only`

## Route
- Namespace: `etherscan`
- Namespace Name: `Etherscan`
- Route Path: `/etherscan/transactions/:address`
- Route Name: `转账追踪`
- Example: `/etherscan/transactions/0x283af0b28c62c092c9727f1ee09c02ca627eb7f5`
- URL: `etherscan.io`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Pretty9`
- Source Location: `transactions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `address`: 地址


## Features
- `requireConfig`: [{"description": "Etherscan API key, can be obtained from https://etherscan.io/myapikey", "name": "ETHERSCAN_API_KEY"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/etherscan/transactions/0x283af0b28c62c092c9727f1ee09c02ca627eb7f5",
  "features": {
    "requireConfig": [
      {
        "description": "Etherscan API key, can be obtained from https://etherscan.io/myapikey",
        "name": "ETHERSCAN_API_KEY"
      }
    ]
  },
  "heat": 0,
  "location": "transactions.ts",
  "maintainers": [
    "Pretty9"
  ],
  "name": "转账追踪",
  "parameters": {
    "address": "地址"
  },
  "path": "/transactions/:address",
  "topFeeds": []
}
```
