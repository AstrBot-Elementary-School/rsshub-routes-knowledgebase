# 9To5 - Sub-site

## Coverage
`index-only`

## Route
- Namespace: `9to5`
- Namespace Name: `9To5`
- Route Path: `/9to5/:subsite/:tag?`
- Route Name: `Sub-site`
- Example: `/9to5/mac/aapl`
- URL: `9to5toys.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `subsite.ts`
- Source Module: `_None_`

## Description
Supported sub-sites：

| 9To5Mac | 9To5Google | 9To5Toys |
| ------- | ---------- | -------- |
| Mac     | Google     | Toys     |

## Parameters
- `subsite`: Subsite name
- `tag`: Tag name inside the url of the tag page


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Supported sub-sites：\n\n| 9To5Mac | 9To5Google | 9To5Toys |\n| ------- | ---------- | -------- |\n| Mac     | Google     | Toys     |",
  "example": "/9to5/mac/aapl",
  "heat": 31,
  "location": "subsite.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Sub-site",
  "parameters": {
    "subsite": "Subsite name",
    "tag": "Tag name inside the url of the tag page"
  },
  "path": "/:subsite/:tag?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Apple News & Mac Rumors Breaking All Day - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63183844748751872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://9to5mac.com/feed/",
      "title": "9To5Mac",
      "type": "feed",
      "url": "rsshub://9to5/mac"
    },
    {
      "description": "Apple News & Mac Rumors Breaking All Day - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62307152241755136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://9to5mac.com/guides/aapl/feed/",
      "title": "aapl | 9To5Mac",
      "type": "feed",
      "url": "rsshub://9to5/mac/aapl"
    }
  ]
}
```
