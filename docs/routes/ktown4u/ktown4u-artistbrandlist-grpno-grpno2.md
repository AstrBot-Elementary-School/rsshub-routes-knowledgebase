# Ktown4u - Get the products on sale

## Coverage
`index-only`

## Route
- Namespace: `ktown4u`
- Namespace Name: `Ktown4u`
- Route Path: `/ktown4u/artistBrandlist/:grpNo/:grpNo2?`
- Route Name: `Get the products on sale`
- Example: `/ktown4u/artistBrandlist/234590/1723449`
- URL: `ktown4u.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `JamesWDGu`
- Source Location: `artist-brandlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `grpNo`: artist id (Get in url)
- `grpNo2`: product category id (Get in url), empty for all categories


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
- `target`: `/artistBrandlist/:grpNo/:grpNo2`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ktown4u/artistBrandlist/234590/1723449",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "artist-brandlist.ts",
  "maintainers": [
    "JamesWDGu"
  ],
  "name": "Get the products on sale",
  "parameters": {
    "grpNo": "artist id (Get in url)",
    "grpNo2": "product category id (Get in url), empty for all categories"
  },
  "path": "/artistBrandlist/:grpNo/:grpNo2?",
  "radar": [
    {
      "source": [],
      "target": "/artistBrandlist/:grpNo/:grpNo2"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ktown4u TAEYEON - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71742086761725952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.ktown4u.com/artistBrandlist?grp_no=4987595&grp_no2=",
      "title": "ktown4u TAEYEON",
      "type": "feed",
      "url": "rsshub://ktown4u/artistBrandlist/4987595"
    },
    {
      "description": "ktown4u MIYEON (i-dle) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69996708519219200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.ktown4u.com/artistBrandlist?grp_no=234590&grp_no2=",
      "title": "ktown4u MIYEON (i-dle)",
      "type": "feed",
      "url": "rsshub://ktown4u/artistBrandlist/234590"
    }
  ]
}
```
