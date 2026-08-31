# 欧乐影院 - 视频

## Coverage
`index-only`

## Route
- Namespace: `olevod`
- Namespace Name: `欧乐影院`
- Route Path: `/olevod/vod/:id`
- Route Name: `视频`
- Example: `/olevod/vod/202449091`
- URL: `olevod.one`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `fang63625`
- Source Location: `vod.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 视频id号


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.olevod.one/vod/:id`
- `target`: `/vod/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/olevod/vod/202449091",
  "features": {
    "nsfw": true
  },
  "heat": 7,
  "location": "vod.ts",
  "maintainers": [
    "fang63625"
  ],
  "name": "视频",
  "parameters": {
    "id": "视频id号"
  },
  "path": "/vod/:id",
  "radar": [
    {
      "source": [
        "www.olevod.one/vod/:id"
      ],
      "target": "/vod/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "画江湖之不良人7 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142611563494446080",
      "image": "https://www.olevod.one/wpimg/202510319.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.olevod.one/vod/202510319",
      "title": "画江湖之不良人7",
      "type": "feed",
      "url": "rsshub://olevod/vod/202510319"
    },
    {
      "description": "灵笼 第二季 - Powered by RSSHub",
      "errorAt": "2026-03-24T07:23:59.136Z",
      "errorMessage": "Failed to fetch\n",
      "id": "163943717183372288",
      "image": "https://www.olevod.one/wpimg/202571099.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.olevod.one/vod/202571099",
      "title": "灵笼 第二季",
      "type": "feed",
      "url": "rsshub://olevod/vod/202571099"
    }
  ]
}
```
