# ChinaFile - Reporting & Opinion

## Coverage
`index-only`

## Route
- Namespace: `chinafile`
- Namespace Name: `ChinaFile`
- Route Path: `/chinafile/:category?`
- Route Name: `Reporting & Opinion`
- Example: `/chinafile/all`
- URL: `www.chinafile.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `oppilate`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Generates full-text feeds that the official feed doesn't provide.

| All | The China NGO Project |
| --- | --------------------- |
| all | ngo                   |

## Parameters
- `category`: Category, by default `all`


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
  "description": "Generates full-text feeds that the official feed doesn't provide.\n\n| All | The China NGO Project |\n| --- | --------------------- |\n| all | ngo                   |",
  "example": "/chinafile/all",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "oppilate"
  ],
  "name": "Reporting & Opinion",
  "parameters": {
    "category": "Category, by default `all`"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "China News, Analysis, Culture, Environment, Media - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "176986240301127681",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinafile.com/",
      "title": "ChinaFile",
      "type": "feed",
      "url": "rsshub://chinafile/all"
    }
  ]
}
```
