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
欄目可用完整的名稱路徑或網頁路徑。
如 `https://www.tkww.hk/top_news/hong_kong` 對應 `top_news/hong_kong` 或 `新聞/香港`。
唯一的目錄名稱也可以單獨使用，例如 `hong_kong`；名稱重複時，請使用完整路徑。
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
### Rule 2
- `source`:
  - `www.tkww.hk/home/*column`
- `target`: `/home/:column`
### Rule 3
- `source`:
  - `www.tkww.hk/top_news/*column`
- `target`: `/top_news/:column`
### Rule 4
- `source`:
  - `www.tkww.hk/video/*column`
- `target`: `/video/:column`
### Rule 5
- `source`:
  - `www.tkww.hk/opinion/*column`
- `target`: `/opinion/:column`
### Rule 6
- `source`:
  - `www.tkww.hk/Go-China/*column`
- `target`: `/Go-China/:column`
### Rule 7
- `source`:
  - `www.tkww.hk/sports/*column`
- `target`: `/sports/:column`
### Rule 8
- `source`:
  - `www.tkww.hk/vohk/*column`
- `target`: `/vohk/:column`
### Rule 9
- `source`:
  - `www.tkww.hk/dwPlan/*column`
- `target`: `/dwPlan/:column`
### Rule 10
- `source`:
  - `www.tkww.hk/spec/*column`
- `target`: `/spec/:column`
### Rule 11
- `source`:
  - `www.tkww.hk/brand/*column`
- `target`: `/brand/:column`
### Rule 12
- `source`:
  - `www.tkww.hk/brandAct/*column`
- `target`: `/brandAct/:column`
### Rule 13
- `source`:
  - `www.tkww.hk/tag/*column`
- `target`: `/tag/:column`
### Rule 14
- `source`:
  - `www.tkww.hk/topics/*column`
- `target`: `/topics/:column`
### Rule 15
- `source`:
  - `www.tkww.hk/info/*column`
- `target`: `/info/:column`
### Rule 16
- `source`:
  - `www.tkww.hk/poll/*column`
- `target`: `/poll/:column`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n欄目可用完整的名稱路徑或網頁路徑。\n如 `https://www.tkww.hk/top_news/hong_kong` 對應 `top_news/hong_kong` 或 `新聞/香港`。\n唯一的目錄名稱也可以單獨使用，例如 `hong_kong`；名稱重複時，請使用完整路徑。\n:::",
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
    },
    {
      "source": [
        "www.tkww.hk/home/*column"
      ],
      "target": "/home/:column"
    },
    {
      "source": [
        "www.tkww.hk/top_news/*column"
      ],
      "target": "/top_news/:column"
    },
    {
      "source": [
        "www.tkww.hk/video/*column"
      ],
      "target": "/video/:column"
    },
    {
      "source": [
        "www.tkww.hk/opinion/*column"
      ],
      "target": "/opinion/:column"
    },
    {
      "source": [
        "www.tkww.hk/Go-China/*column"
      ],
      "target": "/Go-China/:column"
    },
    {
      "source": [
        "www.tkww.hk/sports/*column"
      ],
      "target": "/sports/:column"
    },
    {
      "source": [
        "www.tkww.hk/vohk/*column"
      ],
      "target": "/vohk/:column"
    },
    {
      "source": [
        "www.tkww.hk/dwPlan/*column"
      ],
      "target": "/dwPlan/:column"
    },
    {
      "source": [
        "www.tkww.hk/spec/*column"
      ],
      "target": "/spec/:column"
    },
    {
      "source": [
        "www.tkww.hk/brand/*column"
      ],
      "target": "/brand/:column"
    },
    {
      "source": [
        "www.tkww.hk/brandAct/*column"
      ],
      "target": "/brandAct/:column"
    },
    {
      "source": [
        "www.tkww.hk/tag/*column"
      ],
      "target": "/tag/:column"
    },
    {
      "source": [
        "www.tkww.hk/topics/*column"
      ],
      "target": "/topics/:column"
    },
    {
      "source": [
        "www.tkww.hk/info/*column"
      ],
      "target": "/info/:column"
    },
    {
      "source": [
        "www.tkww.hk/poll/*column"
      ],
      "target": "/poll/:column"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "香港新聞，香港時事，資訊更新更快、聲音更全面、解讀更權威。 - Powered by RSSHub",
      "errorAt": "2025-12-23T14:16:46.461Z",
      "errorMessage": "Invalid Column: hong_kong\n",
      "id": "71128480939804672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tkww.hk/hong_kong",
      "title": "香港 - 大公文匯網",
      "type": "feed",
      "url": "rsshub://tkww/hong_kong"
    },
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
    }
  ]
}
```
