# 万维书刊网 - 学术资讯

## Coverage
`index-only`

## Route
- Namespace: `eshukan`
- Namespace Name: `万维书刊网`
- Route Path: `/eshukan/academic/:id?`
- Route Name: `学术资讯`
- Example: `/eshukan/academic/1`
- URL: `www.eshukan.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `academic.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [期刊动态](https://www.eshukan.com/academic/index.aspx?cid=1)，网址为 `https://www.eshukan.com/academic/index.aspx?cid=1`。截取 `https://www.eshukan.com/academic/index.aspx?cid=` 到末尾的部分 `1` 作为参数填入，此时路由为 [`/eshukan/academic/1`](https://rsshub.app/eshukan/academic/1)。
:::

## Parameters
- `category`: 栏目 id，默认为 `1`，即期刊动态，可在对应栏目页 URL 中找到


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
  - `www.eshukan.com/academic/index.aspx`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "::: tip\n若订阅 [期刊动态](https://www.eshukan.com/academic/index.aspx?cid=1)，网址为 `https://www.eshukan.com/academic/index.aspx?cid=1`。截取 `https://www.eshukan.com/academic/index.aspx?cid=` 到末尾的部分 `1` 作为参数填入，此时路由为 [`/eshukan/academic/1`](https://rsshub.app/eshukan/academic/1)。\n:::",
  "example": "/eshukan/academic/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "academic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "学术资讯",
  "parameters": {
    "category": "栏目 id，默认为 `1`，即期刊动态，可在对应栏目页 URL 中找到"
  },
  "path": "/academic/:id?",
  "radar": [
    {
      "source": [
        "www.eshukan.com/academic/index.aspx"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "滑动拼图验证码 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74645687509395456",
      "image": "https://www.eshukan.com/undefined",
      "ownerUserId": null,
      "siteUrl": "https://www.eshukan.com/academic/index.aspx?cid=1",
      "title": "滑动拼图验证码",
      "type": "feed",
      "url": "rsshub://eshukan/academic/1"
    }
  ],
  "url": "www.eshukan.com"
}
```
