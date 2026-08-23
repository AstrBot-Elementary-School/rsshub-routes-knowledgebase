# 孔夫子旧书网 - 店铺上架

## Coverage
`index-only`

## Route
- Namespace: `kongfz`
- Namespace Name: `孔夫子旧书网`
- Route Path: `/kongfz/shop/:id/:cat?`
- Route Name: `店铺上架`
- Example: `/kongfz/shop/10067/1`
- URL: `kongfz.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `shop.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 店铺 id, 可在对应店铺页 URL 中找到
- `cat`: 分类 id，可在对应分类页 URL 中找到，默认为店铺最新上架


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/kongfz/shop/10067/1",
  "heat": 0,
  "location": "shop.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "店铺上架",
  "parameters": {
    "cat": "分类 id，可在对应分类页 URL 中找到，默认为店铺最新上架",
    "id": "店铺 id, 可在对应店铺页 URL 中找到"
  },
  "path": "/shop/:id/:cat?",
  "topFeeds": []
}
```
