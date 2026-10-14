# JapanGov - 感染症発生動向調査週報

## Coverage
`index-only`

## Route
- Namespace: `go`
- Namespace Name: `JapanGov`
- Route Path: `/go/jihs/idwr/:year?`
- Route Name: `感染症発生動向調査週報`
- Example: `/go/jihs/idwr/2025`
- URL: `id-info.jihs.go.jp`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `jihs/idwr.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [感染症発生動向調査週報](https://id-info.jihs.go.jp/surveillance/idwr/idwr/2025/), where the source URL is `https://id-info.jihs.go.jp/surveillance/idwr/idwr/2025/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/go/jihs/idwr/2025`](https://rsshub.app/go/jihs/idwr/2025).
:::

## Parameters
- `year`: {"description": "Year, current year by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `id-info.jihs.go.jp/surveillance/idwr/idwr/:year`
- `target`: `/jihs/idwr/:year`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\nTo subscribe to [感染症発生動向調査週報](https://id-info.jihs.go.jp/surveillance/idwr/idwr/2025/), where the source URL is `https://id-info.jihs.go.jp/surveillance/idwr/idwr/2025/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/go/jihs/idwr/2025`](https://rsshub.app/go/jihs/idwr/2025).\n:::",
  "example": "/go/jihs/idwr/2025",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jihs/idwr.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "感染症発生動向調査週報",
  "parameters": {
    "year": {
      "description": "Year, current year by default"
    }
  },
  "path": "/jihs/idwr/:year?",
  "radar": [
    {
      "source": [
        "id-info.jihs.go.jp/surveillance/idwr/idwr/:year"
      ],
      "target": "/jihs/idwr/:year"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "id-info.jihs.go.jp",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [传染病发生动向调查周报](https://id-info.jihs.go.jp/surveillance/idwr/idwr/2025/)，网址为 `https://id-info.jihs.go.jp/surveillance/idwr/idwr/2025/`，请截取 `https://id-info.jihs.go.jp/surveillance/idwr/idwr/` 到末尾 `/` 的部分 `2025` 作为 `year` 参数填入，此时目标路由为 [`/go/jihs/idwr/2025`](https://rsshub.app/go/jihs/idwr/2025)。\n:::",
    "name": "传染病发生动向调查周报",
    "parameters": {
      "year": {
        "description": "年份，默认为当前年份，可在对应页 URL 中找到"
      }
    }
  }
}
```
