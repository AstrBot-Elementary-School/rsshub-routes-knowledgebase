# 秀动网 - 按城市 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/showstart/event/:cityCode/:showStyle?`
- Route Name: `按城市 - 演出更新`
- Example: `/showstart/event/571/3`
- URL: `www.showstart.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `event.ts`
- Source Module: `_None_`

## Description
::: tip

- 演出城市 `cityCode` 查询: `/showstart/search/city/:keyword`, 如: [https://rsshub.app/showstart/search/city/ 杭州](https://rsshub.app/showstart/search/city/杭州)

- 演出风格 `showStyle` 查询: `/showstart/search/style/:keyword`，如: [https://rsshub.app/showstart/search/style/ 摇滚](https://rsshub.app/showstart/search/style/摇滚)

:::

## Parameters
- `cityCode`: 演出城市 (编号)
- `showStyle`: 演出风格 (编号)


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
    "shopping"
  ],
  "description": "::: tip\n\n- 演出城市 `cityCode` 查询: `/showstart/search/city/:keyword`, 如: [https://rsshub.app/showstart/search/city/ 杭州](https://rsshub.app/showstart/search/city/杭州)\n\n- 演出风格 `showStyle` 查询: `/showstart/search/style/:keyword`，如: [https://rsshub.app/showstart/search/style/ 摇滚](https://rsshub.app/showstart/search/style/摇滚)\n\n:::",
  "example": "/showstart/event/571/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 40,
  "location": "event.ts",
  "maintainers": [
    "lchtao26"
  ],
  "name": "按城市 - 演出更新",
  "parameters": {
    "cityCode": "演出城市 (编号)",
    "showStyle": "演出风格 (编号)"
  },
  "path": "/event/:cityCode/:showStyle?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "秀动网 - 杭州 - 摇滚 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68586319985771520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 杭州 - 摇滚",
      "type": "feed",
      "url": "rsshub://showstart/event/571/2"
    },
    {
      "description": "秀动网 - 上海 - 摇滚 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67433992246280192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 上海 - 摇滚",
      "type": "feed",
      "url": "rsshub://showstart/event/21/2"
    }
  ]
}
```
