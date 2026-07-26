# Google - Alerts

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/alerts/:keyword`
- Route Name: `Alerts`
- Example: `/google/alerts/RSSHub`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `alerts.ts`
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

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/google/alerts/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 34,
  "location": "alerts.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Alerts",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/alerts/:keyword",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Google Alerts - 中国经营报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "153319458878542848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Google Alerts - 中国经营报",
      "type": "feed",
      "url": "rsshub://google/alerts/%E4%B8%AD%E5%9B%BD%E7%BB%8F%E8%90%A5%E6%8A%A5"
    },
    {
      "description": "Google Alerts - 中国社会科学院工业经济研究所 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "153319230023687168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Google Alerts - 中国社会科学院工业经济研究所",
      "type": "feed",
      "url": "rsshub://google/alerts/%E4%B8%AD%E5%9B%BD%E7%A4%BE%E4%BC%9A%E7%A7%91%E5%AD%A6%E9%99%A2%E5%B7%A5%E4%B8%9A%E7%BB%8F%E6%B5%8E%E7%A0%94%E7%A9%B6%E6%89%80"
    }
  ]
}
```
