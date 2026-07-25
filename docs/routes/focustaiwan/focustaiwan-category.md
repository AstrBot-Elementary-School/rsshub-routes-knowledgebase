# Focus Taiwan - Category

## Coverage
`index-only`

## Route
- Namespace: `focustaiwan`
- Namespace Name: `Focus Taiwan`
- Route Path: `/focustaiwan/:category?`
- Route Name: `Category`
- Example: `/focustaiwan`
- URL: `focustaiwan.tw`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| Latest | Editor's Picks | Photos of the Day |
| ------ | -------------- | ----------------- |
| news   | editorspicks   | photos            |

| Politics | Cross-strait | Business | Society | Science & Tech | Culture | Sports |
| -------- | ------------ | -------- | ------- | -------------- | ------- | ------ |
| politics | cross-strait | business | society | science & tech | culture | sports |

## Parameters
- `category`: 分类，见下表，默认为 news


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Latest | Editor's Picks | Photos of the Day |\n| ------ | -------------- | ----------------- |\n| news   | editorspicks   | photos            |\n\n| Politics | Cross-strait | Business | Society | Science & Tech | Culture | Sports |\n| -------- | ------------ | -------- | ------- | -------------- | ------- | ------ |\n| politics | cross-strait | business | society | science & tech | culture | sports |",
  "example": "/focustaiwan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "分类，见下表，默认为 news"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Latest | Focus Taiwan - CNA English News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73313031910916096",
      "image": "https://imgcdn.cna.com.tw/Eng/website/img/default.png",
      "ownerUserId": null,
      "siteUrl": "https://focustaiwan.tw/news",
      "title": "Latest | Focus Taiwan - CNA English News",
      "type": "feed",
      "url": "rsshub://focustaiwan"
    }
  ]
}
```
