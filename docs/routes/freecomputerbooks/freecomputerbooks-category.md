# Free Computer Books - Book List

## Coverage
`index-only`

## Route
- Namespace: `freecomputerbooks`
- Namespace Name: `Free Computer Books`
- Route Path: `/freecomputerbooks/:category?`
- Route Name: `Book List`
- Example: `/freecomputerbooks/compscAlgorithmBooks`
- URL: `freecomputerbooks.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `cubroe`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: A category id., which should be the HTML file name (but **without** the `.html` suffix) in the URL path of a book list page.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `freecomputerbooks.com/`
  - `freecomputerbooks.com/index.html`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/freecomputerbooks/compscAlgorithmBooks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 267,
  "location": "index.tsx",
  "maintainers": [
    "cubroe"
  ],
  "name": "Book List",
  "parameters": {
    "category": "A category id., which should be the HTML file name (but **without** the `.html` suffix) in the URL path of a book list page."
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "freecomputerbooks.com/",
        "freecomputerbooks.com/index.html"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Free Computer, Programming, Mathematics, Technical Books, Lecture Notes and Tutorials - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62187667731240962",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://freecomputerbooks.com/",
      "title": "Free Computer Books - Selected New Books",
      "type": "feed",
      "url": "rsshub://freecomputerbooks"
    },
    {
      "description": "Algorithms and Data Structures - Free Computer, Programming, Mathematics, Technical Books, Lecture Notes and Tutorials - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59843947513404416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://freecomputerbooks.com/compscAlgorithmBooks.html",
      "title": "Free Computer Books - Algorithms and Data Structures",
      "type": "feed",
      "url": "rsshub://freecomputerbooks/compscAlgorithmBooks"
    }
  ],
  "url": "freecomputerbooks.com"
}
```
