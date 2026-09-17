# 新唐人电视台 - 频道

## Coverage
`index-only`

## Route
- Namespace: `ntdtv`
- Namespace Name: `新唐人电视台`
- Route Path: `/ntdtv/:language/:id`
- Route Name: `频道`
- Example: `/ntdtv/b5/prog1201`
- URL: `www.ntdtv.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Fatpandac`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
参数均可在官网获取，如：

`https://www.ntdtv.com/b5/prog1201` 对应 `/ntdtv/b5/prog1201`

## Parameters
- `language`: 语言，简体为`gb`，繁体为`b5`
- `id`: 子频道名称


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
  - `www.ntdtv.com/:language/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "参数均可在官网获取，如：\n\n`https://www.ntdtv.com/b5/prog1201` 对应 `/ntdtv/b5/prog1201`",
  "example": "/ntdtv/b5/prog1201",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 131,
  "location": "channel.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "id": "子频道名称",
    "language": "语言，简体为`gb`，繁体为`b5`"
  },
  "path": "/:language/:id",
  "radar": [
    {
      "source": [
        "www.ntdtv.com/:language/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新唐人电视台 - 时政 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69975679174674432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ntdtv.com/gb/prog1201",
      "title": "新唐人电视台 - 时政",
      "type": "feed",
      "url": "rsshub://ntdtv/gb/prog1201"
    },
    {
      "description": "新唐人电视台 - 大陆 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148402521198272512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ntdtv.com/gb/prog204",
      "title": "新唐人电视台 - 大陆",
      "type": "feed",
      "url": "rsshub://ntdtv/gb/prog204"
    }
  ]
}
```
