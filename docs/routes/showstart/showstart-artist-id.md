# 秀动网 - 按音乐人 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/showstart/artist/:id`
- Route Name: `按音乐人 - 演出更新`
- Example: `/showstart/artist/301783`
- URL: `www.showstart.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `artist.ts`
- Source Module: `_None_`

## Description
::: tip
音乐人 ID 查询: `/showstart/search/artist/:keyword`，如: [https://rsshub.app/showstart/search/artist/ 周杰伦](https://rsshub.app/showstart/search/artist/周杰伦)
:::

## Parameters
- `id`: 音乐人 ID


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
  - `www.showstart.com/artist/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n音乐人 ID 查询: `/showstart/search/artist/:keyword`，如: [https://rsshub.app/showstart/search/artist/ 周杰伦](https://rsshub.app/showstart/search/artist/周杰伦)\n:::",
  "example": "/showstart/artist/301783",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "artist.ts",
  "maintainers": [
    "lchtao26"
  ],
  "name": "按音乐人 - 演出更新",
  "parameters": {
    "id": "音乐人 ID"
  },
  "path": "/artist/:id",
  "radar": [
    {
      "source": [
        "www.showstart.com/artist/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "秀动网 - 周士爵 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59224265617690624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/6810007",
      "title": "秀动网 - 周士爵",
      "type": "feed",
      "url": "rsshub://showstart/artist/6810007"
    },
    {
      "description": "内地独立流行乐团，由主唱乔西、词曲创作刘冠南组成。代表作《呼吸决定》、《忘了我》、《没有人不比我快乐》。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73918360042176532",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/992554",
      "title": "秀动网 - Fine乐团",
      "type": "feed",
      "url": "rsshub://showstart/artist/992554"
    }
  ]
}
```
