# Radio-Canada.ca - Latest News

## Coverage
`index-only`

## Route
- Namespace: `radio-canada`
- Namespace Name: `Radio-Canada.ca`
- Route Path: `/radio-canada/latest/:language?`
- Route Name: `Latest News`
- Example: `/radio-canada/latest`
- URL: `ici.radio-canada.ca`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `latest.ts`
- Source Module: `_None_`

## Description
| Français | English | Español | 简体中文 | 繁體中文 | العربية | ਪੰਜਾਬੀ | Tagalog |
| -------- | ------- | ------- | -------- | -------- | ------- | --- | ------- |
| fr       | en      | es      | zh-hans  | zh-hant  | ar      | pa  | tl      |

## Parameters
- `language`: Language, see below, English by default


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
  - `ici.radio-canada.ca/rci/:lang`
  - `ici.radio-canada.ca/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Français | English | Español | 简体中文 | 繁體中文 | العربية | ਪੰਜਾਬੀ | Tagalog |\n| -------- | ------- | ------- | -------- | -------- | ------- | --- | ------- |\n| fr       | en      | es      | zh-hans  | zh-hant  | ar      | pa  | tl      |",
  "example": "/radio-canada/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "latest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Latest News",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/latest/:language?",
  "radar": [
    {
      "source": [
        "ici.radio-canada.ca/rci/:lang",
        "ici.radio-canada.ca/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "加拿大国际广播电台 | Radio-Canada.ca - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59770798244269056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ici.radio-canada.ca/rci/zh_hans/%E6%9C%80%E6%96%B0%E6%96%B0%E9%97%BB",
      "title": "加拿大国际广播电台 | Radio-Canada.ca",
      "type": "feed",
      "url": "rsshub://radio-canada/latest/zh-hans"
    },
    {
      "description": "Radio Canada International | Radio-Canada.ca - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73549081174574080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ici.radio-canada.ca/rci/en/latest-news",
      "title": "Radio Canada International | Radio-Canada.ca",
      "type": "feed",
      "url": "rsshub://radio-canada/latest"
    }
  ]
}
```
