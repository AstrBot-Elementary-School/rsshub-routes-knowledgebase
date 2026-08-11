# 东北大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `neu`
- Namespace Name: `东北大学`
- Route Path: `/neu/news/:type`
- Route Name: `新闻网`
- Example: `/neu/news/ddyw`
- URL: `neunews.neu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `JeasonLau`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 种类名   | 参数 |
| -------- | ---- |
| 东大要闻 | ddyw |
| 媒体东大 | mtdd |
| 通知公告 | tzgg |
| 新闻纵横 | xwzh |
| 人才培养 | rcpy |
| 学术科研 | xsky |
| 英文新闻 | 217  |
| 招生就业 | zsjy |
| 考研出国 | kycg |
| 校园文学 | xywx |
| 校友风采 | xyfc |
| 时事热点 | ssrd |
| 教育前沿 | jyqy |
| 文化体育 | whty |
| 最新科技 | zxkj |

## Parameters
- `type`: 种类名，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `neunews.neu.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 种类名   | 参数 |\n| -------- | ---- |\n| 东大要闻 | ddyw |\n| 媒体东大 | mtdd |\n| 通知公告 | tzgg |\n| 新闻纵横 | xwzh |\n| 人才培养 | rcpy |\n| 学术科研 | xsky |\n| 英文新闻 | 217  |\n| 招生就业 | zsjy |\n| 考研出国 | kycg |\n| 校园文学 | xywx |\n| 校友风采 | xyfc |\n| 时事热点 | ssrd |\n| 教育前沿 | jyqy |\n| 文化体育 | whty |\n| 最新科技 | zxkj |",
  "example": "/neu/news/ddyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "JeasonLau"
  ],
  "name": "新闻网",
  "parameters": {
    "type": "种类名，见下表"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "neunews.neu.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
