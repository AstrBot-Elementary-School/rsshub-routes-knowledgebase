# Go 语言中文网 - 板块

## Coverage
`index-only`

## Route
- Namespace: `studygolang`
- Namespace Name: `Go 语言中文网`
- Route Path: `/studygolang/go/:id?`
- Route Name: `板块`
- Example: `/studygolang/go/daily`
- URL: `studygolang.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `go.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 板块 id，默认为周刊


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
  - `studygolang.com/go/:id`
  - `studygolang.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/studygolang/go/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 318,
  "location": "go.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "板块",
  "parameters": {
    "id": "板块 id，默认为周刊"
  },
  "path": "/go/:id?",
  "radar": [
    {
      "source": [
        "studygolang.com/go/:id",
        "studygolang.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Go语言中文网 - Go周刊 - Powered by RSSHub",
      "errorAt": "2026-07-21T11:07:02.170Z",
      "errorMessage": "[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\nAuthentication failed. Access denied.\n/studygolang/go\n[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\n[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\n[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\n",
      "id": "56597687648785408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://studygolang.com/go/weekly",
      "title": "Go语言中文网 - Go周刊",
      "type": "feed",
      "url": "rsshub://studygolang/go"
    },
    {
      "description": "Go语言中文网 - 每日一学 - Powered by RSSHub",
      "errorAt": "2026-07-22T01:40:56.050Z",
      "errorMessage": "Authentication failed. Access denied.\n/studygolang/go/daily\n[GET] \"https://studygolang.com/go/daily\": 502 Bad Gateway\n[GET] \"https://studygolang.com/go/daily\": 502 Bad Gateway\n[GET] \"https://studygolang.com/go/daily\": 502 Bad Gateway\n",
      "id": "54846819419389955",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://studygolang.com/go/daily",
      "title": "Go语言中文网 - 每日一学",
      "type": "feed",
      "url": "rsshub://studygolang/go/daily"
    }
  ]
}
```
