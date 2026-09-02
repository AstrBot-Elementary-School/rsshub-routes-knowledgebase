# ZAKER - 分类

## Coverage
`index-only`

## Route
- Namespace: `zaker`
- Namespace Name: `ZAKER`
- Route Path: `/zaker/channel/:id?`
- Route Name: `分类`
- Example: `/zaker/channel/13`
- URL: `myzaker.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `LogicJake, kt286, TonyRL`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分类 ID，可在 URL 中找到，默认为 `1`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.myzaker.com/channel/:id`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/zaker/channel/13",
  "heat": 48,
  "location": "channel.ts",
  "maintainers": [
    "LogicJake",
    "kt286",
    "TonyRL"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 ID，可在 URL 中找到，默认为 `1`"
  },
  "path": "/channel/:id?",
  "radar": [
    {
      "source": [
        "www.myzaker.com/channel/:id"
      ],
      "target": "/channel/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "科技 - ZAKER新闻 - Powered by RSSHub",
      "errorAt": "2026-09-01T09:37:29.148Z",
      "errorMessage": "Invalid RSSHub JSON Feed from 98292582055262208\n[GET] \"https://www.myzaker.com/channel/13\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 60.200.32.49:443, 60.200.32.50:443, 60.200.32.43:443, 60.200.32.44:443, 60.200.32.45:443, 60.200.32.46:443, 60.200.32.47:443, 60.200.32.48:443, timeout: 10000ms))\n",
      "id": "56326657469609999",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.myzaker.com/channel/13",
      "title": "科技 - ZAKER新闻",
      "type": "feed",
      "url": "rsshub://zaker/channel/13"
    },
    {
      "description": "ZAKER新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "109858197894680576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.myzaker.com/channel/660",
      "title": "ZAKER新闻",
      "type": "feed",
      "url": "rsshub://zaker/channel/660"
    }
  ]
}
```
