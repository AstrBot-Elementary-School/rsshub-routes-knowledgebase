# 乳首ふぇち - Tag

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/chikubi/tag/:keyword`
- Route Name: `Tag`
- Example: `/chikubi/tag/ドリームチケット`
- URL: `chikubi.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `Tag`
- `source`:
  - `chikubi.jp/tag/:keyword`
- `target`: `/tag/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/tag/ドリームチケット",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "tag.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Tag",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/tag/:keyword",
  "radar": [
    {
      "source": [
        "chikubi.jp/tag/:keyword"
      ],
      "target": "/tag/:keyword",
      "title": "Tag"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Tag: ドリームチケット - chikubi.jp - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67431890670912512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chikubi.jp/category/%E3%83%89%E3%83%AA%E3%83%BC%E3%83%A0%E3%83%81%E3%82%B1%E3%83%83%E3%83%88",
      "title": "Tag: ドリームチケット - chikubi.jp",
      "type": "feed",
      "url": "rsshub://chikubi/tag/%E3%83%89%E3%83%AA%E3%83%BC%E3%83%A0%E3%83%81%E3%82%B1%E3%83%83%E3%83%88"
    }
  ]
}
```
