# National Geographic - 分类

## Coverage
`index-only`

## Route
- Namespace: `natgeo`
- Namespace Name: `National Geographic`
- Route Path: `/natgeo/:cat/:type?`
- Route Name: `分类`
- Example: `/natgeo/environment/article`
- URL: `nationalgeographic.com`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `fengkx`
- Source Location: `natgeo.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cat`: 分类
- `type`: 类型, 例如`https://www.natgeomedia.com/environment/photo/`对应 `cat`, `type` 分别为 `environment`, `photo`


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
  - `natgeomedia.com/:cat/:type`
  - `natgeomedia.com/:cat/`
  - `natgeomedia.com/`
- `target`: `/:cat/:type?`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/natgeo/environment/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 306,
  "location": "natgeo.ts",
  "maintainers": [
    "fengkx"
  ],
  "name": "分类",
  "parameters": {
    "cat": "分类",
    "type": "类型, 例如`https://www.natgeomedia.com/environment/photo/`对应 `cat`, `type` 分别为 `environment`, `photo`"
  },
  "path": "/:cat/:type?",
  "radar": [
    {
      "source": [
        "natgeomedia.com/:cat/:type",
        "natgeomedia.com/:cat/",
        "natgeomedia.com/"
      ],
      "target": "/:cat/:type?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "國家地理雜誌｜呈現最新的自然、科學、生態與文化專題報導。探索動物保護、環境變遷、考古發現等豐富內容，並通過精美的攝影和深度分析，帶您深入了解世界各地的故事與現象。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59442359778246659",
      "image": "https://www.natgeomedia.com/img/app_icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.natgeomedia.com/environment/article",
      "title": "文章總匯 - 國家地理雜誌官方網站｜探索自然、科學與文化的最佳權",
      "type": "feed",
      "url": "rsshub://natgeo/environment/article"
    },
    {
      "description": "國家地理雜誌｜呈現最新的自然、科學、生態與文化專題報導。探索動物保護、環境變遷、考古發現等豐富內容，並通過精美的攝影和深度分析，帶您深入了解世界各地的故事與現象。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67036766288113664",
      "image": "https://www.natgeomedia.com/img/app_icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.natgeomedia.com/travel/photo",
      "title": "每日一圖 - 國家地理雜誌官方網站｜探索自然、科學與文化的最佳權",
      "type": "feed",
      "url": "rsshub://natgeo/travel/photo"
    }
  ]
}
```
