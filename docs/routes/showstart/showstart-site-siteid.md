# 秀动网 - 按场地 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/showstart/site/:siteId`
- Route Name: `按场地 - 演出更新`
- Example: `/showstart/site/3583`
- URL: `www.showstart.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `site.ts`
- Source Module: `_None_`

## Description
::: tip

- 演出场地 ID 查询: `/showstart/search/site/:keyword`, 如: [https://rsshub.app/showstart/search/site/ 酒球会](https://rsshub.app/showstart/search/site/酒球会)

:::

## Parameters
- `siteId`: 演出场地 (编号)


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
  - `www.showstart.com/venue/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n\n- 演出场地 ID 查询: `/showstart/search/site/:keyword`, 如: [https://rsshub.app/showstart/search/site/ 酒球会](https://rsshub.app/showstart/search/site/酒球会)\n\n:::",
  "example": "/showstart/site/3583",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 102,
  "location": "site.ts",
  "maintainers": [
    "lchtao26"
  ],
  "name": "按场地 - 演出更新",
  "parameters": {
    "siteId": "演出场地 (编号)"
  },
  "path": "/site/:siteId",
  "radar": [
    {
      "source": [
        "www.showstart.com/venue/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海市长宁区绥宁路820号 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68851013929552896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 上海 - 回响之地 Music Park",
      "type": "feed",
      "url": "rsshub://showstart/site/18165038"
    },
    {
      "description": "广州市海珠区南洲路154号（侨建·HICITY ）2F 207 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70160608790705152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 广州 - SDlivehouse",
      "type": "feed",
      "url": "rsshub://showstart/site/3515"
    }
  ]
}
```
