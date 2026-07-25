# 知园 - Newsletter

## Coverage
`index-only`

## Route
- Namespace: `zhiy`
- Namespace Name: `知园`
- Route Path: `/zhiy/letters/:author`
- Route Name: `Newsletter`
- Example: `/zhiy/letters/messy`
- URL: `zhiy.cc`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `letter.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `author`: 作者 ID，可在URL中找到


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
  - `zhiy.cc/:author`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/zhiy/letters/messy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 48,
  "location": "letter.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Newsletter",
  "parameters": {
    "author": "作者 ID，可在URL中找到"
  },
  "path": "/letters/:author",
  "radar": [
    {
      "source": [
        "zhiy.cc/:author"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "潦草学者 的思考与感受 关注个人成长、效率工具和互联网商业。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55130722692595724",
      "image": "https://zhiycc.oss-cn-beijing.aliyuncs.com/public/legacy/ce7679f0750a7fe1c109f80ed0d660d0/ce7679f0750a7fe1c109f80ed0d660d0",
      "ownerUserId": null,
      "siteUrl": "https://zhiy.cc/messy",
      "title": "草稿拾遗",
      "type": "feed",
      "url": "rsshub://zhiy/letters/messy"
    },
    {
      "description": "流媒体与创作者经济的深度观察 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56252214742450176",
      "image": "https://zhiycc.oss-cn-beijing.aliyuncs.com/public/legacy/1ed6deaaa522dee8f8487f1aa9acefec/1ed6deaaa522dee8f8487f1aa9acefec",
      "ownerUserId": null,
      "siteUrl": "https://zhiy.cc/upstream",
      "title": "逆流Upstream",
      "type": "feed",
      "url": "rsshub://zhiy/letters/upstream"
    }
  ]
}
```
