# 第一财经 - 一财号

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/yicai/author/:id?`
- Route Name: `一财号`
- Example: `/yicai/author/100005663`
- URL: `yicai.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在对应作者页中找到，默认为第一财经研究院


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
  - `yicai.com/author/:id`
  - `yicai.com/author`
- `target`: `/author/:id?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/yicai/author/100005663",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "author.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "一财号",
  "parameters": {
    "id": "作者 id，可在对应作者页中找到，默认为第一财经研究院"
  },
  "path": "/author/:id?",
  "radar": [
    {
      "source": [
        "yicai.com/author/:id",
        "yicai.com/author"
      ],
      "target": "/author/:id?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
