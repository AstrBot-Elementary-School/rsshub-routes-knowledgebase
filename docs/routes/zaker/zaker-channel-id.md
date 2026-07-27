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
  "heat": 49,
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
      "errorAt": "2026-07-25T17:52:15.391Z",
      "errorMessage": "Authentication failed. Access denied.\n/zaker/channel/13\n[GET] \"https://www.myzaker.com/article/6a6430698e9f0951f03828bd\": 429 Too Many Requests\nCannot read properties of undefined (reading 'article')\n",
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
      "errorAt": "2026-07-24T05:40:51.652Z",
      "errorMessage": "[GET] \"https:https://app.myzaker.com/news/topic.php?topic_id=6a6550228e9f09764740d9d4\": <no response> fetch failed (getaddrinfo ENOTFOUND https)\n",
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
