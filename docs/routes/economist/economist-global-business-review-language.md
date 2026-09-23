# The Economist - Global Business Review

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/economist/global-business-review/:language?`
- Route Name: `Global Business Review`
- Example: `/economist/global-business-review/cn-en`
- URL: `businessreview.global/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `prnake`
- Source Location: `global-business-review.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Language, `en`, `cn`, `tw` are supported, support multiple options, default to cn-en


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
  - `businessreview.global/`
- `target`: `/global-business-review`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/economist/global-business-review/cn-en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "global-business-review.ts",
  "maintainers": [
    "prnake"
  ],
  "name": "Global Business Review",
  "parameters": {
    "language": "Language, `en`, `cn`, `tw` are supported, support multiple options, default to cn-en"
  },
  "path": "/global-business-review/:language?",
  "radar": [
    {
      "source": [
        "businessreview.global/"
      ],
      "target": "/global-business-review"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-01T11:07:40.126Z",
      "errorMessage": "[GET] \"https://api.hummingbird.businessreview.global/api/toc/get_articles\": 530 \n",
      "id": "151955931879114755",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://economist/global-business-review/cn-en"
    }
  ],
  "url": "businessreview.global/"
}
```
