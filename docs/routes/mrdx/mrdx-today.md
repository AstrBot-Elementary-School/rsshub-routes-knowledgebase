# 新华每日电讯 - 今日

## Coverage
`index-only`

## Route
- Namespace: `mrdx`
- Namespace Name: `新华每日电讯`
- Route Path: `/mrdx/today`
- Route Name: `今日`
- Example: `/mrdx/today`
- URL: `mrdx.cn*`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Dustin-Jiang`
- Source Location: `daily.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `mrdx.cn*`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/mrdx/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 423,
  "location": "daily.ts",
  "maintainers": [
    "Dustin-Jiang"
  ],
  "name": "今日",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "mrdx.cn*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国报纸发行前三强。位列《人民日报》，《参考消息》之后。《新华每日电讯》是新华社出版的一份新闻电讯报，1993年创办，具有很高的权威性和准确性，有“一报在手，便知天下”之美誉。《新华每日电讯》为对开八版日报，集中刊登[新华社]每天向国内播发的电讯稿及图片稿。打开《新华每日电讯》，中国和全世界每天发生的重大事件便将一目了然。在人类生活节奏日益加快的当今世界，《新华每日电讯》以最便捷、最醒目的方式为公众提供最重要的新闻报道，受到公众的喜爱和拥护。 - Powered by RSSHub",
      "errorAt": "2026-07-01T16:32:53.006Z",
      "errorMessage": "[GET] \"http://mrdx.cn/content/20260803/Page01DK.htm\": 404 Not Found\n[GET] \"http://mrdx.cn/content/20260803/Page01DK.htm\": 404 Not Found\n[GET] \"http://mrdx.cn/content/20260803/Page01DK.htm\": 404 Not Found\n",
      "id": "64309222369856512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://mrdx.cn/content/20260701/Page01DK.htm",
      "title": "新华每日电讯",
      "type": "feed",
      "url": "rsshub://mrdx/today"
    }
  ],
  "url": "mrdx.cn*"
}
```
