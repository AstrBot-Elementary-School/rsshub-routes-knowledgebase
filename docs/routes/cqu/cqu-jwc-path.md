# 重庆大学 - 本科教学信息网通知

## Coverage
`index-only`

## Route
- Namespace: `cqu`
- Namespace Name: `重庆大学`
- Route Path: `/cqu/jwc/:path{.+}?`
- Route Name: `本科教学信息网通知`
- Example: `/cqu/jwc/index/tzgg`
- URL: `cqu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `El-Chiang, Hagb, AhsokaTano26`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: {"default": "index/tzgg", "description": "路径参数，默认为 `index/tzgg`，也支持官网的 `index/tzgg.htm` 路径"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.cqu.edu.cn/index/:filename`
- `target`: `/jwc/index/:filename`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cqu/jwc/index/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "El-Chiang",
    "Hagb",
    "AhsokaTano26"
  ],
  "name": "本科教学信息网通知",
  "parameters": {
    "path": {
      "default": "index/tzgg",
      "description": "路径参数，默认为 `index/tzgg`，也支持官网的 `index/tzgg.htm` 路径"
    }
  },
  "path": "/jwc/:path{.+}?",
  "radar": [
    {
      "source": [
        "jwc.cqu.edu.cn/index/:filename"
      ],
      "target": "/jwc/index/:filename"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
