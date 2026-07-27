# U3C3 - Search

## Coverage
`index-only`

## Route
- Namespace: `u3c3`
- Namespace Name: `U3C3`
- Route Path: `/u3c3/search/:keyword/:preview?`
- Route Name: `Search`
- Example: `/u3c3/search/新片速递`
- URL: `u3c3.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `storytellerF`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Search keyword
- `preview`: Show image preview, off by default, non empty value means on


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/u3c3/search/新片速递",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 48,
  "location": "index.ts",
  "maintainers": [
    "storytellerF"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Search keyword",
    "preview": "Show image preview, off by default, non empty value means on"
  },
  "path": [
    "/search/:keyword/:preview?",
    "/:type?/:preview?"
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "search 新片速递 - u3c3 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68549075258311680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.u3c3.com/?search2=psnpyckc&search=%E6%96%B0%E7%89%87%E9%80%9F%E9%80%92",
      "title": "search 新片速递 - u3c3",
      "type": "feed",
      "url": "rsshub://u3c3/search/%E6%96%B0%E7%89%87%E9%80%9F%E9%80%92"
    },
    {
      "description": "search U3C3 - u3c3 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131696291531404288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.u3c3.com/?search2=yzzs8s6c&search=U3C3",
      "title": "search U3C3 - u3c3",
      "type": "feed",
      "url": "rsshub://u3c3/search/U3C3"
    }
  ]
}
```
