# 南京理工大学 - 电光学院研学网

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/njust/dgxg/:type?`
- Route Name: `电光学院研学网`
- Example: `/njust/dgxg/gstz`
- URL: `jwc.njust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `dgxg.ts`
- Source Module: `_None_`

## Description
| 公示通知 | 学术文化 | 就业指导 |
| -------- | -------- | -------- |
| gstz     | xswh     | jyzd     |

## Parameters
- `type`: 分类名，见下表，默认为公示通知


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公示通知 | 学术文化 | 就业指导 |\n| -------- | -------- | -------- |\n| gstz     | xswh     | jyzd     |",
  "example": "/njust/dgxg/gstz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dgxg.ts",
  "maintainers": [
    "jasongzy"
  ],
  "name": "电光学院研学网",
  "parameters": {
    "type": "分类名，见下表，默认为公示通知"
  },
  "path": "/dgxg/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
