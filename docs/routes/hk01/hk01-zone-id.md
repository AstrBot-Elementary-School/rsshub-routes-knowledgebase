# 香港 01 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `hk01`
- Namespace Name: `香港 01`
- Route Path: `/hk01/zone/:id?`
- Route Name: `栏目`
- Example: `/hk01/zone/11`
- URL: `hk01.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `hoilc, Fatpandac, nczitzk`
- Source Location: `zone.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 栏目 id, 可在 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `hk01.com/zone/:id`
  - `hk01.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hk01/zone/11",
  "heat": 147,
  "location": "zone.ts",
  "maintainers": [
    "hoilc",
    "Fatpandac",
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id, 可在 URL 中找到"
  },
  "path": "/zone/:id?",
  "radar": [
    {
      "source": [
        "hk01.com/zone/:id",
        "hk01.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "港聞 | 香港01 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67391706472795145",
      "image": "https://cdn.hk01.com/di/media/images/dw/20201125/408227309540085760319542.jpeg/d8hq2b6WibciRCsMNd7W2yLPmgpIT5f7HaSF0B2khdA",
      "ownerUserId": null,
      "siteUrl": "https://hk01.com/zone/1",
      "title": "港聞 | 香港01",
      "type": "feed",
      "url": "rsshub://hk01/zone/1"
    },
    {
      "description": "觀點 | 香港01 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67391706472795143",
      "image": "https://cdn.hk01.com/di/media/images/dw/20201125/408228012966809600968521.png/iLSX3aBqMJua0Gc3o1pEMySDayDl34CKLKMCpiyjAqY",
      "ownerUserId": null,
      "siteUrl": "https://hk01.com/zone/12",
      "title": "觀點 | 香港01",
      "type": "feed",
      "url": "rsshub://hk01/zone/12"
    }
  ]
}
```
