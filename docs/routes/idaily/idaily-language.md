# iDaily - 每日环球视野

## Coverage
`index-only`

## Route
- Namespace: `idaily`
- Namespace Name: `iDaily`
- Route Path: `/idaily/:language?`
- Route Name: `每日环球视野`
- Example: `/idaily`
- URL: `idai.ly`
- Language: `_None_`
- Categories: `other`
- Maintainers: `zphw, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 简体中文 | 繁体中文 |
| -------- | -------- |
| zh-hans  | zh-hant  |

## Parameters
- `language`: 语言，见下表，默认为简体中文


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `idai.ly/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 简体中文 | 繁体中文 |\n| -------- | -------- |\n| zh-hans  | zh-hant  |",
  "example": "/idaily",
  "heat": 574,
  "location": "index.tsx",
  "maintainers": [
    "zphw",
    "nczitzk"
  ],
  "name": "每日环球视野",
  "parameters": {
    "language": "语言，见下表，默认为简体中文"
  },
  "path": "/:language?",
  "radar": [
    {
      "source": [
        "idai.ly/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "iDaily · 每日环球视野 | Your Global Point of View - Powered by RSSHub",
      "errorAt": "2026-10-17T04:06:56.623Z",
      "errorMessage": "[GET] \"https://idai.ly\": 522 <none>\n",
      "id": "56593152747053056",
      "image": "https://idai.ly/img/idaily/logo_2x.png",
      "ownerUserId": null,
      "siteUrl": "https://idai.ly/",
      "title": "iDaily · 每日环球视野",
      "type": "feed",
      "url": "rsshub://idaily"
    },
    {
      "description": "iDaily · 每日环球视野 | Your Global Point of View - Powered by RSSHub",
      "errorAt": "2026-10-17T04:08:45.728Z",
      "errorMessage": "[GET] \"https://idai.ly\": <no response> fetch failed\n[GET] \"https://idai.ly\": <no response> fetch failed (Connect Timeout Error (attempted address: idai.ly:443, timeout: 10000ms))\n[GET] \"https://idai.ly\": <no response> fetch failed\n[GET] \"https://idai.ly\": <no response> fetch failed\nInvalid language. Use zh-hans or zh-hant.\n",
      "id": "53257967622553618",
      "image": "https://idai.ly/img/idaily/logo_2x.png",
      "ownerUserId": null,
      "siteUrl": "https://idai.ly/",
      "title": "iDaily · 每日环球视野",
      "type": "feed",
      "url": "rsshub://idaily/today"
    }
  ]
}
```
