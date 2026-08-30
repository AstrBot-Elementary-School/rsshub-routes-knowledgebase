# 禁忌书屋 - 禁忌书屋

## Coverage
`index-only`

## Route
- Namespace: `cool18`
- Namespace Name: `禁忌书屋`
- Route Path: `/cool18/:id?/:type?/:keyword?`
- Route Name: `禁忌书屋`
- Example: `/cool18/bbs4`
- URL: `cool18.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk, Gabrlie`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: the name of the bbs, use `global` for site-wide search
- `type`: the type of the post. Can be `home`, `gold`, `threadsearch`. Default: `home`
- `keyword`: the keyword to search.


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `cool18.com/:id/`
- `target`: `/:id/:type?/:keyword?`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/cool18/bbs4",
  "features": {
    "nsfw": true
  },
  "heat": 1212,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "Gabrlie"
  ],
  "name": "禁忌书屋",
  "parameters": {
    "id": "the name of the bbs, use `global` for site-wide search",
    "keyword": "the keyword to search.",
    "type": "the type of the post. Can be `home`, `gold`, `threadsearch`. Default: `home`"
  },
  "path": "/:id?/:type?/:keyword?",
  "radar": [
    {
      "source": [
        "cool18.com/:id/"
      ],
      "target": "/:id/:type?/:keyword?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "禁忌书屋 cool18 酷18 - Powered by RSSHub",
      "errorAt": "2026-08-23T15:16:36.581Z",
      "errorMessage": "200 ",
      "id": "149578173744708608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cool18.com/bbs4/index.php",
      "title": "禁忌书屋 cool18 酷18",
      "type": "feed",
      "url": "rsshub://cool18"
    },
    {
      "description": "性趣贴图 cool18 酷18 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154611732391264308",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cool18.com/bbs/index.php",
      "title": "性趣贴图 cool18 酷18",
      "type": "feed",
      "url": "rsshub://cool18/bbs"
    }
  ],
  "url": "cool18.com"
}
```
