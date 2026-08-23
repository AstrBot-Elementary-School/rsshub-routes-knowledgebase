# 数字尾巴 - 鲸图（排行榜）

## Coverage
`index-only`

## Route
- Namespace: `dgtle`
- Namespace Name: `数字尾巴`
- Route Path: `/dgtle/whale/rank/:type/:rule`
- Route Name: `鲸图（排行榜）`
- Example: `/dgtle/whale/rank/download/day`
- URL: `dgtle.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Erriy`
- Source Location: `whale-rank.ts`
- Source Module: `_None_`

## Description
type

| 下载排行榜 | 点赞排行榜 |
| ---------- | ---------- |
| download   | like       |

rule

| 日排行 | 周排行 | 月排行 | 总排行 |
| ------ | ------ | ------ | ------ |
| day    | week   | month  | amount |

## Parameters
- `type`: 排行榜类型
- `rule`: 排行榜周期


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
  "description": "type\n\n| 下载排行榜 | 点赞排行榜 |\n| ---------- | ---------- |\n| download   | like       |\n\nrule\n\n| 日排行 | 周排行 | 月排行 | 总排行 |\n| ------ | ------ | ------ | ------ |\n| day    | week   | month  | amount |",
  "example": "/dgtle/whale/rank/download/day",
  "heat": 0,
  "location": "whale-rank.ts",
  "maintainers": [
    "Erriy"
  ],
  "name": "鲸图（排行榜）",
  "parameters": {
    "rule": "排行榜周期",
    "type": "排行榜类型"
  },
  "path": "/whale/rank/:type/:rule",
  "topFeeds": []
}
```
