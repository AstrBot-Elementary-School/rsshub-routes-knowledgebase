# The Economist - Espresso

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/economist/espresso`
- Route Name: `Espresso`
- Example: `/economist/espresso`
- URL: `economist.com/the-world-in-brief`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `TonyRL`
- Source Location: `espresso.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `economist.com/the-world-in-brief`
  - `economist.com/espresso`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "example": "/economist/espresso",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2168,
  "location": "espresso.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Espresso",
  "parameters": {},
  "path": "/espresso",
  "radar": [
    {
      "source": [
        "economist.com/the-world-in-brief",
        "economist.com/espresso"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Catch up quickly on the global stories that matter - Powered by RSSHub",
      "errorAt": "2025-09-07T13:19:15.831Z",
      "errorMessage": "[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\nAuthentication failed. Access denied.\n/economist/espresso\n[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\n[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\n[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\nAuthentication failed. Access denied.\n/economist/espresso\n[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\n[GET] \"https://www.economist.com/the-world-in-brief\": <no response> fetch failed\n502 \n[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\n[GET] \"https://www.economist.com/the-world-in-brief\": 403 Forbidden\n",
      "id": "41572238278099968",
      "image": "https://www.economist.com/engassets/World-OG-image.png",
      "ownerUserId": null,
      "siteUrl": "https://www.economist.com/the-world-in-brief",
      "title": "The world in brief | The Economist",
      "type": "feed",
      "url": "rsshub://economist/espresso"
    }
  ],
  "url": "economist.com/the-world-in-brief",
  "view": 0
}
```
