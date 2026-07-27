# 澎湃新闻 - 明查

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/thepaper/factpaper/:status?`
- Route Name: `明查`
- Example: `/thepaper/factpaper`
- URL: `factpaper.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `factpaper.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `status`: 状态 id，可选 `1` 即 有定论 或 `0` 即 核查中，默认为 `1`


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
  - `factpaper.cn/`
- `target`: `/factpaper/:status`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thepaper/factpaper",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 97,
  "location": "factpaper.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "明查",
  "parameters": {
    "status": "状态 id，可选 `1` 即 有定论 或 `0` 即 核查中，默认为 `1`"
  },
  "path": "/factpaper/:status?",
  "radar": [
    {
      "source": [
        "factpaper.cn/"
      ],
      "target": "/factpaper/:status"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "澎湃明查 - 有定论 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59189169883828224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.factpaper.cn/",
      "title": "澎湃明查 - 有定论",
      "type": "feed",
      "url": "rsshub://thepaper/factpaper"
    },
    {
      "description": "澎湃明查 - 有定论 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85894831444113408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.factpaper.cn/",
      "title": "澎湃明查 - 有定论",
      "type": "feed",
      "url": "rsshub://thepaper/factpaper/1"
    }
  ],
  "url": "factpaper.cn/"
}
```
