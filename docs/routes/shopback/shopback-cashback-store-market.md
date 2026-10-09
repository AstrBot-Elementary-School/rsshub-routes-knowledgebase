# ShopBack - Merchant cashback rates

## Coverage
`index-only`

## Route
- Namespace: `shopback`
- Namespace Name: `ShopBack`
- Route Path: `/shopback/cashback/:store/:market?`
- Route Name: `Merchant cashback rates`
- Example: `/shopback/cashback/agoda/tw`
- URL: `shopback.com.tw`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `DIYgod`
- Source Location: `cashback.ts`
- Source Module: `_None_`

## Description
Includes the merchant’s current cashback rates. Each distinct product-and-rate combination has a separate GUID. A return to a previously seen rate reuses its earlier GUID. The former product/search and store/search endpoints are no longer available.

## Parameters
- `store`: Merchant slug from its ShopBack URL.
- `market`: tw (default), my, sg, th, kr, au, id, or ph.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.shopback.com.tw/:store`
- `target`: `/cashback/:store/tw`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Includes the merchant’s current cashback rates. Each distinct product-and-rate combination has a separate GUID. A return to a previously seen rate reuses its earlier GUID. The former product/search and store/search endpoints are no longer available.",
  "example": "/shopback/cashback/agoda/tw",
  "heat": 0,
  "location": "cashback.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Merchant cashback rates",
  "parameters": {
    "market": "tw (default), my, sg, th, kr, au, id, or ph.",
    "store": "Merchant slug from its ShopBack URL."
  },
  "path": "/cashback/:store/:market?",
  "radar": [
    {
      "source": [
        "www.shopback.com.tw/:store"
      ],
      "target": "/cashback/:store/tw"
    }
  ],
  "topFeeds": []
}
```
