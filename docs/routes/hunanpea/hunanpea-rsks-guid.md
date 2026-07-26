# 湖南人事考试网 - 公告

## Coverage
`index-only`

## Route
- Namespace: `hunanpea`
- Namespace Name: `湖南人事考试网`
- Route Path: `/hunanpea/rsks/:guid`
- Route Name: `公告`
- Example: `/hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e`
- URL: `rsks.hunanpea.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `TonyRL`
- Source Location: `rsks.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `guid`: 分类 id，可在 URL 中找到


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
  - `rsks.hunanpea.com/Category/:guid/ArticlesByCategory.do`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "rsks.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "公告",
  "parameters": {
    "guid": "分类 id，可在 URL 中找到"
  },
  "path": "/rsks/:guid",
  "radar": [
    {
      "source": [
        "rsks.hunanpea.com/Category/:guid/ArticlesByCategory.do"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新闻公告 - 湖南人事考试网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65998206582691840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://rsks.hunanpea.com/Category/2f1a6239-b4dc-491b-92af-7d95e0f0543e/ArticlesByCategory.do?PageIndex=1",
      "title": "新闻公告 - 湖南人事考试网",
      "type": "feed",
      "url": "rsshub://hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e"
    },
    {
      "description": "公务员及事业单位考试 - 湖南人事考试网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62787884154546176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://rsks.hunanpea.com/Category/c5a6f516-fd54-4578-90bd-0cb6a1c95570/ArticlesByCategory.do?PageIndex=1",
      "title": "公务员及事业单位考试 - 湖南人事考试网",
      "type": "feed",
      "url": "rsshub://hunanpea/rsks/c5a6f516-fd54-4578-90bd-0cb6a1c95570"
    }
  ]
}
```
