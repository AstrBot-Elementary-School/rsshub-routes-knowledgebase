# 古诗文网 - 首页推荐

## Coverage
`index-only`

## Route
- Namespace: `gushiwen`
- Namespace Name: `古诗文网`
- Route Path: `/gushiwen/recommend/:annotation?`
- Route Name: `首页推荐`
- Example: `/gushiwen/recommend/zhushang`
- URL: `www.gushiwen.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `LogicJake`
- Source Location: `recommend.ts`
- Source Module: `_None_`

## Description
`annotation` 字段为添加哪些附加信息。可从以下表格中选择值后按顺序拼接。例如如果需要注释和赏析，则为`zhushang`。

| 翻译 | 注释 | 赏析  |
| ---- | ---- | ----- |
| yi   | zhu  | shang |

## Parameters
- `annotation`: 添加哪些附加信息


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "`annotation` 字段为添加哪些附加信息。可从以下表格中选择值后按顺序拼接。例如如果需要注释和赏析，则为`zhushang`。\n\n| 翻译 | 注释 | 赏析  |\n| ---- | ---- | ----- |\n| yi   | zhu  | shang |",
  "example": "/gushiwen/recommend/zhushang",
  "heat": 1,
  "location": "recommend.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "首页推荐",
  "parameters": {
    "annotation": "添加哪些附加信息"
  },
  "path": "/recommend/:annotation?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "古诗文推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896292778067",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gushiwen.cn/",
      "title": "古诗文推荐",
      "type": "feed",
      "url": "rsshub://gushiwen/recommend/yizhushang"
    }
  ]
}
```
