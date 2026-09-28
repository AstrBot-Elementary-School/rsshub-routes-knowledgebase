# Google - Play Store Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/play/:id/:lang?`
- Route Name: `Play Store Update`
- Example: `/google/play/net.dinglisch.android.taskerm`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `surwall`
- Source Location: `play.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Package id, can be found in url
- `lang`: {"default": "en-us", "description": "language", "options": [{"label": "English", "value": "en-us"}, {"label": "简体中文", "value": "zh-cn"}]}


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
  - `play.google.com/store/apps/details?id=:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/google/play/net.dinglisch.android.taskerm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "play.ts",
  "maintainers": [
    "surwall"
  ],
  "name": "Play Store Update",
  "parameters": {
    "id": "Package id, can be found in url",
    "lang": {
      "default": "en-us",
      "description": "language",
      "options": [
        {
          "label": "English",
          "value": "en-us"
        },
        {
          "label": "简体中文",
          "value": "zh-cn"
        }
      ]
    }
  },
  "path": "/play/:id/:lang?",
  "radar": [
    {
      "source": [
        "play.google.com/store/apps/details?id=:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Tasker - Google Play - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "215327803838904320",
      "image": "https://play-lh.googleusercontent.com/wjXpkVLT-LAzfcYOfhH0hF8ghU79nDHtqVLxBNmWOQJ2ghb4pgp_IBNfGdCTw-aQgh3WwA3Gp1k8Y4waZkGobmA",
      "ownerUserId": null,
      "siteUrl": "https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en&gl=us",
      "title": "Tasker - Google Play",
      "type": "feed",
      "url": "rsshub://google/play/net.dinglisch.android.taskerm"
    }
  ]
}
```
