# 德阳人事考试网 - 考试新闻发布

## Coverage
`index-only`

## Route
- Namespace: `dykszx`
- Namespace Name: `德阳人事考试网`
- Route Path: `/dykszx/news/:newsType?`
- Route Name: `考试新闻发布`
- Example: `/dykszx/news`
- URL: `www.dykszx.com`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zytomorrow`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 新闻中心 | 公务员考试 | 事业单位 | （职）业资格、职称考试 |  其他 |
| :------: | :--------: | :------: | :--------------------: | :---: |
|    all   |     gwy    |   sydw   |          zyzc          | other |

## Parameters
- `newsType`: 考试类型。默认新闻中心(all)


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
  - `www.dykszx.com/`
- `target`: `/news/all`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻中心 | 公务员考试 | 事业单位 | （职）业资格、职称考试 |  其他 |\n| :------: | :--------: | :------: | :--------------------: | :---: |\n|    all   |     gwy    |   sydw   |          zyzc          | other |",
  "example": "/dykszx/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "news.ts",
  "maintainers": [
    "zytomorrow"
  ],
  "name": "考试新闻发布",
  "parameters": {
    "newsType": "考试类型。默认新闻中心(all)"
  },
  "path": "/news/:newsType?",
  "radar": [
    {
      "source": [
        "www.dykszx.com/"
      ],
      "target": "/news/all"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "德阳人事考试网 考试新闻发布 (新闻中心) - Powered by RSSHub",
      "errorAt": "2025-10-09T02:43:18.643Z",
      "errorMessage": "[GET] \"https://www.dykszx.com\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 222.213.85.69:443, 240e:699:1c01:712:5298:3ab3:6d3:1b5b:443, timeout: 10000ms))\n",
      "id": "61102289930311680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dykszx.com/",
      "title": "考试新闻发布(新闻中心)",
      "type": "feed",
      "url": "rsshub://dykszx/news"
    },
    {
      "description": "德阳人事考试网 考试新闻发布 (其他考试) - Powered by RSSHub",
      "errorAt": "2025-10-09T01:22:44.835Z",
      "errorMessage": "[GET] \"https://www.dykszx.com\": <no response> fetch failed\n",
      "id": "161655081002352640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dykszx.com/",
      "title": "考试新闻发布(其他考试)",
      "type": "feed",
      "url": "rsshub://dykszx/news/other"
    }
  ],
  "url": "www.dykszx.com"
}
```
