# Followin - KOL

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/followin/kol/:kolId/:lang?`
- Route Name: `KOL`
- Example: `/followin/kol/4075592991`
- URL: `followin.io`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `kol.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `kolId`: KOL ID, can be found in URL
- `lang`: Language, see table above, `en` by default


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
  - `followin.io/:lang/kol/:kolId`
  - `followin.io/kol/:kolId`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/kol/4075592991",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "kol.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "KOL",
  "parameters": {
    "kolId": "KOL ID, can be found in URL",
    "lang": "Language, see table above, `en` by default"
  },
  "path": "/kol/:kolId/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang/kol/:kolId",
        "followin.io/kol/:kolId"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "关注人工智能、LLM 、 AI 图像视频和设计（Interested in AI, LLM, Stable Diffusion, and design） AIGC 周刊主理人｜公众号：歸藏的AI工具箱 - Powered by RSSHub",
      "errorAt": "2026-09-02T04:10:00.498Z",
      "errorMessage": "[GET] \"https://followin.io\": 429 Too Many Requests\n",
      "id": "152340239177418752",
      "image": "https://static.fwimg.io/img/user/cd2305bdad53876f2aa8a29c7b7ac950.jpg",
      "ownerUserId": null,
      "siteUrl": "https://followin.io/zh-Hans/kol/4075685147",
      "title": "歸藏(guizang.ai) - Followin",
      "type": "feed",
      "url": "rsshub://followin/kol/4075685147/zh-Hans"
    },
    {
      "description": "Cryptocurrency News - Powered by RSSHub",
      "errorAt": "2026-08-20T00:58:09.590Z",
      "errorMessage": "[GET] \"https://followin.io\": 429 Too Many Requests\n",
      "id": "69315953676176384",
      "image": "https://static.fwimg.io/img/user/7024bd1650e88fecd407590437ebc50dae75497d",
      "ownerUserId": null,
      "siteUrl": "https://followin.io/zh-Hans/kol/4075649237",
      "title": "BeInCrypto - Followin",
      "type": "feed",
      "url": "rsshub://followin/kol/4075649237/zh-Hans"
    }
  ]
}
```
