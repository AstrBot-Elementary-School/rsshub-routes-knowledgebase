# 大公文匯網 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `tkww`
- Namespace Name: `大公文匯網`
- Route Path: `/tkww/:column{.+}?`
- Route Name: `新聞`
- Example: `/tkww/hong_kong`
- URL: `www.tkww.hk`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
欄目可用`名稱`或對應網頁的`path`，
如 `https://www.tkww.hk/hong_kong` 的欄目可以填`香港`或是`hong_kong`
而 `https://www.tkww.hk/china/shanghai` 的欄目則需填`china/shanghai`
:::

## Parameters
- `column`: 欄目，默認為 home (首頁)


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.tkww.hk/:column`
- `target`: `/:column`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n欄目可用`名稱`或對應網頁的`path`，\n如 `https://www.tkww.hk/hong_kong` 的欄目可以填`香港`或是`hong_kong`\n而 `https://www.tkww.hk/china/shanghai` 的欄目則需填`china/shanghai`\n:::",
  "example": "/tkww/hong_kong",
  "features": {
    "antiCrawler": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 83,
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "新聞",
  "parameters": {
    "column": "欄目，默認為 home (首頁)"
  },
  "path": "/:column{.+}?",
  "radar": [
    {
      "source": [
        "www.tkww.hk/:column"
      ],
      "target": "/:column"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "大公文匯網是香港大公文匯傳媒集團官方網站。香港大公文匯傳媒集團成立於2016年1月，旗下有《大公報》、香港《文匯報》、《香港仔》等報章和大公文匯網、大公網、香港文匯網及覆蓋移動端、社交媒體的多個網站新媒體平台，是立足香港、國際視野的愛國愛港傳媒集團。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70533090955148288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tkww.hk/",
      "title": "首頁 - 大公文匯網",
      "type": "feed",
      "url": "rsshub://tkww"
    },
    {
      "description": "香港新聞，香港時事，資訊更新更快、聲音更全面、解讀更權威。 - Powered by RSSHub",
      "errorAt": "2025-12-23T14:16:46.461Z",
      "errorMessage": "Invalid Column: hong_kong\nInvalid Column: hong_kong\n",
      "id": "71128480939804672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tkww.hk/hong_kong",
      "title": "香港 - 大公文匯網",
      "type": "feed",
      "url": "rsshub://tkww/hong_kong"
    }
  ]
}
```
