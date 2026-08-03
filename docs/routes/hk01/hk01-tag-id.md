# 香港 01 - 标签

## Coverage
`index-only`

## Route
- Namespace: `hk01`
- Namespace Name: `香港 01`
- Route Path: `/hk01/tag/:id?`
- Route Name: `标签`
- Example: `/hk01/tag/2787`
- URL: `hk01.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `hoilc, Fatpandac, nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 标签 id, 可在 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `hk01.com/tag/:id`
  - `hk01.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hk01/tag/2787",
  "heat": 11,
  "location": "tag.ts",
  "maintainers": [
    "hoilc",
    "Fatpandac",
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "id": "标签 id, 可在 URL 中找到"
  },
  "path": "/tag/:id?",
  "radar": [
    {
      "source": [
        "hk01.com/tag/:id",
        "hk01.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "365 | 香港01 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87141419213215744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hk01.com/tag/365",
      "title": "365 | 香港01",
      "type": "feed",
      "url": "rsshub://hk01/tag/365"
    },
    {
      "description": "13102 | 香港01 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92006333948699648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hk01.com/tag/13102",
      "title": "13102 | 香港01",
      "type": "feed",
      "url": "rsshub://hk01/tag/13102"
    }
  ]
}
```
