# 聯合新聞網 - 轉角國際 - 標籤

## Coverage
`index-only`

## Route
- Namespace: `udn`
- Namespace Name: `聯合新聞網`
- Route Path: `/udn/global/tag/:tag?`
- Route Name: `轉角國際 - 標籤`
- Example: `/udn/global/tag/過去24小時`
- URL: `udn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `emdoe, nczitzk, pseudoyu`
- Source Location: `global/tag.ts`
- Source Module: `_None_`

## Description
| 過去 24 小時 | 鏡頭背後 | 深度專欄 | 重磅廣播 |
| ------------ | -------- | -------- | -------- |

## Parameters
- `tag`: 标签，可在对应标签页 URL 中找到


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
  - `global.udn.com/search/tagging/1020/:tag`
  - `global.udn.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 過去 24 小時 | 鏡頭背後 | 深度專欄 | 重磅廣播 |\n| ------------ | -------- | -------- | -------- |",
  "example": "/udn/global/tag/過去24小時",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "global/tag.ts",
  "maintainers": [
    "emdoe",
    "nczitzk",
    "pseudoyu"
  ],
  "name": "轉角國際 - 標籤",
  "parameters": {
    "tag": "标签，可在对应标签页 URL 中找到"
  },
  "path": "/global/tag/:tag?",
  "radar": [
    {
      "source": [
        "global.udn.com/search/tagging/1020/:tag",
        "global.udn.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "轉角國際 udn Global - 過去24小時 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69916583666986003",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://global.udn.com/search/tagging/1020/%E9%81%8E%E5%8E%BB24%E5%B0%8F%E6%99%82",
      "title": "轉角國際 udn Global - 過去24小時",
      "type": "feed",
      "url": "rsshub://udn/global/tag/%E9%81%8E%E5%8E%BB24%E5%B0%8F%E6%99%82"
    },
    {
      "description": "轉角國際 udn Global - 深度專欄 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80781985075075072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://global.udn.com/search/tagging/1020/%E6%B7%B1%E5%BA%A6%E5%B0%88%E6%AC%84",
      "title": "轉角國際 udn Global - 深度專欄",
      "type": "feed",
      "url": "rsshub://udn/global/tag/%E6%B7%B1%E5%BA%A6%E5%B0%88%E6%AC%84"
    }
  ]
}
```
