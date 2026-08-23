# gihyo.jp - Series

## Coverage
`index-only`

## Route
- Namespace: `gihyo`
- Namespace Name: `gihyo.jp`
- Route Path: `/gihyo/list/group/:id`
- Route Name: `Series`
- Example: `/gihyo/list/group/Ubuntu-Weekly-Recipe`
- URL: `gihyo.jp`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `yuanji-dev`
- Source Location: `group.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Series


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
  - `gihyo.jp/list/group/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gihyo/list/group/Ubuntu-Weekly-Recipe",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "group.ts",
  "maintainers": [
    "yuanji-dev"
  ],
  "name": "Series",
  "parameters": {
    "id": "Series"
  },
  "path": "/list/group/:id",
  "radar": [
    {
      "source": [
        "gihyo.jp/list/group/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Ubuntu Weekly Recipeの記事一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68855551480439836",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gihyo.jp/list/group/Ubuntu-Weekly-Recipe",
      "title": "Ubuntu Weekly Recipe | gihyo.jp",
      "type": "feed",
      "url": "rsshub://gihyo/list/group/Ubuntu-Weekly-Recipe"
    }
  ]
}
```
