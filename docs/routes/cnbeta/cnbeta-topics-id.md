# cnBeta.COM - 主题

## Coverage
`index-only`

## Route
- Namespace: `cnbeta`
- Namespace Name: `cnBeta.COM`
- Route Path: `/cnbeta/topics/:id`
- Route Name: `主题`
- Example: `/cnbeta/topics/453`
- URL: `cnbeta.com.tw`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `cczhong11, nczitzk`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
::: tip
完整的主题列表参见 [主题列表](https://www.cnbeta.com.tw/topics.htm)
:::

## Parameters
- `id`: 主题 id，可在对应主题页的 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cnbeta.com.tw/topics/:id`
  - `www.cnbeta.com.tw/topics/:id`
- `target`: `/topics/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n完整的主题列表参见 [主题列表](https://www.cnbeta.com.tw/topics.htm)\n:::",
  "example": "/cnbeta/topics/453",
  "heat": 3,
  "location": "topics.ts",
  "maintainers": [
    "cczhong11",
    "nczitzk"
  ],
  "name": "主题",
  "parameters": {
    "id": "主题 id，可在对应主题页的 URL 中找到"
  },
  "path": "/topics/:id",
  "radar": [
    {
      "source": [
        "cnbeta.com.tw/topics/:id",
        "www.cnbeta.com.tw/topics/:id"
      ],
      "target": "/topics/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "cnBeta.COM - 中文业界资讯站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69244938999805952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cnbeta.com.tw/",
      "title": "cnBeta.COM - 中文业界资讯站",
      "type": "feed",
      "url": "rsshub://cnbeta/topics/453"
    }
  ],
  "url": "cnbeta.com.tw"
}
```
