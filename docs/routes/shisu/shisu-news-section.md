# 上海外国语大学 - 上外新闻

## Coverage
`index-only`

## Route
- Namespace: `shisu`
- Namespace Name: `上海外国语大学`
- Route Path: `/shisu/news/:section`
- Route Name: `上外新闻`
- Example: `/shisu/news/news`
- URL: `shisu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Duuckjing`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 首页 | 特稿    | 学术      | 教学       | 国际          | 校园   | 人物   | 视讯       | 公告   |
| ---- | ------- | --------- | ---------- | ------------- | ------ | ------ | ---------- | ------ |
| news | gazette | research- | academics- | international | campus | people | multimedia | notice |

## Parameters
- `section`: 主站的新闻类别


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
  - `news.shisu.edu.cn/:section/index.html`
- `target`: `/news/:section`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 首页 | 特稿    | 学术      | 教学       | 国际          | 校园   | 人物   | 视讯       | 公告   |\n| ---- | ------- | --------- | ---------- | ------------- | ------ | ------ | ---------- | ------ |\n| news | gazette | research- | academics- | international | campus | people | multimedia | notice |",
  "example": "/shisu/news/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "Duuckjing"
  ],
  "name": "上外新闻",
  "parameters": {
    "section": "主站的新闻类别"
  },
  "path": "/news/:section",
  "radar": [
    {
      "source": [
        "news.shisu.edu.cn/:section/index.html"
      ],
      "target": "/news/:section"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上外新闻|SISU TODAY - Notice - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83443825223243776",
      "image": "https://upload.wikimedia.org/wikipedia/zh/thumb/0/06/Shanghai_International_Studies_University_logo.svg/300px-Shanghai_International_Studies_University_logo.svg.png",
      "ownerUserId": null,
      "siteUrl": "https://news.shisu.edu.cn/notice/index.html",
      "title": "上外新闻|SISU TODAY - Notice",
      "type": "feed",
      "url": "rsshub://shisu/news/notice"
    }
  ]
}
```
