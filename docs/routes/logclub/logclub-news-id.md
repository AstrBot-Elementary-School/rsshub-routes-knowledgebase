# 罗戈网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `logclub`
- Namespace Name: `罗戈网`
- Route Path: `/logclub/news/:id?`
- Route Name: `资讯`
- Example: `/logclub/news`
- URL: `logclub.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 供应链 | 快递 | 快运 / 运输 | 仓储 / 地产 | 物流综合 | 国际与跨境物流 | 科技创新 |
| ------ | ---- | ----------- | ----------- | -------- | -------------- | -------- |
| 10-16  | 11   | 30          | 9           | 32       | 114            | 107      |

| 绿色供应链 | 低碳物流 | 碳中和碳达峰 |
| ---------- | -------- | ------------ |
| 213        | 214      | 215          |

## Parameters
- `id`: 资讯 id，见下表，可在对应资讯页 URL 中找到，默认为全部


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `logclub.com/news`
- `target`: `/news`
### Rule 2
- `source`:
  - `logclub.com/news/:id`
- `target`: `/news/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 供应链 | 快递 | 快运 / 运输 | 仓储 / 地产 | 物流综合 | 国际与跨境物流 | 科技创新 |\n| ------ | ---- | ----------- | ----------- | -------- | -------------- | -------- |\n| 10-16  | 11   | 30          | 9           | 32       | 114            | 107      |\n\n| 绿色供应链 | 低碳物流 | 碳中和碳达峰 |\n| ---------- | -------- | ------------ |\n| 213        | 214      | 215          |",
  "example": "/logclub/news",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "id": "资讯 id，见下表，可在对应资讯页 URL 中找到，默认为全部"
  },
  "path": "/news/:id?",
  "radar": [
    {
      "source": [
        "logclub.com/news"
      ],
      "target": "/news"
    },
    {
      "source": [
        "logclub.com/news/:id"
      ],
      "target": "/news/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
