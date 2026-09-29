# kpopping - Pics

## Coverage
`index-only`

## Route
- Namespace: `kpopping`
- Namespace Name: `kpopping`
- Route Path: `/kpopping/kpics/:filter{.+}?`
- Route Name: `Pics`
- Example: `/kpopping/kpics/gender=female&category=musicshow&idolId=a1664634-5caf-45d3-a57f-49d99d929aa9`
- URL: `kpopping.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk, pinapelz`
- Source Location: `kpics.ts`
- Source Module: `_None_`

## Description
::: tip
Query photos using filter parameters found on kpopping such as `idolId`, `groupId`, `gender`, `category`, `sort`, etc.
:::

## Parameters
- `filter`: Filter parameters in `key=value&key2=value2` format. Supported keys: `category`, `gender`, `sort`, `entityType`, `idolId`, `groupId`


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
  - `kpopping.com/kpics`
- `target`: `/kpics`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\nQuery photos using filter parameters found on kpopping such as `idolId`, `groupId`, `gender`, `category`, `sort`, etc.\n:::",
  "example": "/kpopping/kpics/gender=female&category=musicshow&idolId=a1664634-5caf-45d3-a57f-49d99d929aa9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 41,
  "location": "kpics.ts",
  "maintainers": [
    "nczitzk",
    "pinapelz"
  ],
  "name": "Pics",
  "parameters": {
    "filter": "Filter parameters in `key=value&key2=value2` format. Supported keys: `category`, `gender`, `sort`, `entityType`, `idolId`, `groupId`"
  },
  "path": "/kpics/:filter{.+}?",
  "radar": [
    {
      "source": [
        "kpopping.com/kpics"
      ],
      "target": "/kpics"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "kpics - kpopping - Powered by RSSHub",
      "errorAt": "2026-09-28T06:25:53.468Z",
      "errorMessage": "[GET] \"https://kpopping.com/api/photos?gender-female%2Fcategory-all%2Fidol-any%2Fgroup-any%2Forder=\": 403 \n[GET] \"https://kpopping.com/api/photos?gender-female%2Fcategory-all%2Fidol-any%2Fgroup-any%2Forder=\": 429 Too Many Requests\n",
      "id": "127912538951825408",
      "image": "https://kpopping.com/build/images/kpopping-default-detailed.jpg",
      "ownerUserId": null,
      "siteUrl": "https://kpopping.com/kpics",
      "title": "kpics - kpopping",
      "type": "feed",
      "url": "rsshub://kpopping/kpics/gender-female/category-all/idol-any/group-any/order"
    },
    {
      "description": "kpics - kpopping - Powered by RSSHub",
      "errorAt": "2026-09-07T14:11:52.222Z",
      "errorMessage": "[GET] \"https://kpopping.com/api/photos\": 429 Too Many Requests\n",
      "id": "160056537743224832",
      "image": "https://kpopping.com/build/images/kpopping-default-detailed.jpg",
      "ownerUserId": null,
      "siteUrl": "https://kpopping.com/kpics",
      "title": "kpics - kpopping",
      "type": "feed",
      "url": "rsshub://kpopping/kpics"
    }
  ],
  "url": "kpopping.com",
  "view": 2,
  "zh": {
    "description": "::: tip\n支持通过 `idolId`、`groupId`、`gender`、`category`、`sort` 等过滤条件获取照片。\n:::",
    "name": "Pics",
    "parameters": {
      "filter": "以 `key=value&key2=value2` 格式传递的过滤参数。支持的 key 包括 `category`、`gender`、`sort`、`entityType`、`idolId`、`groupId`"
    }
  }
}
```
