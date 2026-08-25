# 巴哈姆特電玩資訊站 - 创作大厅

## Coverage
`index-only`

## Route
- Namespace: `gamer`
- Namespace Name: `巴哈姆特電玩資訊站`
- Route Path: `/gamer/creation_index/:category?/:subcategory?/:type?`
- Route Name: `创作大厅`
- Example: `/gamer/creation_index/4/0/2`
- URL: `acg.gamer.com.tw`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `creation-index.ts`
- Source Module: `_None_`

## Description
分类 ID 参考如下

| 不限 | 日誌 | 小說 | 繪圖 | Cosplay | 同人商品 |
| ---- | ---- | ---- | ---- | ------- | -------- |
| 0    | 1    | 2    | 3    | 4       | 5        |

子分类 ID 比较多不作列举

排行类型参考如下

| 達人專欄 | 最新創作 | 最新推薦 | 熱門創作 | 精選閣樓 |
| -------- | -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        | 5        |

## Parameters
- `category`: 分类 ID, 即为 URL 中 `k1` 参数, 0 或置空为不限
- `subcategory`: 子分类 ID, 即为 URL 中 `k2` 参数, 0 或置空为不限
- `type`: 排行类型, 即为 URL 中 `vt` 参数, 0 或置空为達人專欄


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "分类 ID 参考如下\n\n| 不限 | 日誌 | 小說 | 繪圖 | Cosplay | 同人商品 |\n| ---- | ---- | ---- | ---- | ------- | -------- |\n| 0    | 1    | 2    | 3    | 4       | 5        |\n\n子分类 ID 比较多不作列举\n\n排行类型参考如下\n\n| 達人專欄 | 最新創作 | 最新推薦 | 熱門創作 | 精選閣樓 |\n| -------- | -------- | -------- | -------- | -------- |\n| 1        | 2        | 3        | 4        | 5        |",
  "example": "/gamer/creation_index/4/0/2",
  "heat": 0,
  "location": "creation-index.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "创作大厅",
  "parameters": {
    "category": "分类 ID, 即为 URL 中 `k1` 参数, 0 或置空为不限",
    "subcategory": "子分类 ID, 即为 URL 中 `k2` 参数, 0 或置空为不限",
    "type": "排行类型, 即为 URL 中 `vt` 参数, 0 或置空为達人專欄"
  },
  "path": "/creation_index/:category?/:subcategory?/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
